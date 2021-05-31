pipeline {
  agent any
  stages {
    stage('阶段 5-1') {
      steps {
        sleep 20
      }
    }
    stage('自定义构建过程') {
      steps {
        echo '自定义构建过程开始'
      }
    }
    stage('阶段 3-1') {
      steps {
        input(message: '是否继续执行构建', submitter: 'hughli@tencent.com')
      }
    }
    stage('阶段 4-1') {
      steps {
        sleep 600
      }
    }
  }
}