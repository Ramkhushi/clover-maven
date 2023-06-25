pipeline {
  agent {
    node {
      label 'stg'
    }

  }
  stages {
    stage('stage1') {
      agent {
    node {
      label 'stg'
    }
      steps {
        echo 'hello world'
      }
    }

  }
}
