pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo \'hello, stage1\''
      }
    }

    stage('stage2') {
      steps {
        sh 'echo \'hello, stage2\''
        git(url: 'https://github.com/Mallika4679/lavanya.git', branch: 'main', poll: true)
      }
    }

  }
}