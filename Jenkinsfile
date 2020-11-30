pipeline {
  agent {
    dockerfile {
      filename './app/py_master/Dockerfile'
    }

  }
  stages {
    stage('Test') {
      agent {
        dockerfile {
          filename 'Dockerfile'
        }

      }
      steps {
        sh ' python --version'
      }
    }

  }
}