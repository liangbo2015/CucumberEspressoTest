pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo '01 build '
          }
        }

        stage('build 02') {
          steps {
            echo '021'
          }
        }

      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo '02 test'
          }
        }

        stage('022') {
          steps {
            echo '022'
          }
        }

      }
    }

    stage('Deploy') {
      parallel {
        stage('Deploy') {
          steps {
            echo '03 deploy'
          }
        }

        stage('023') {
          steps {
            echo '023'
          }
        }

      }
    }

  }
  environment {
    PATH = 'cccc'
  }
}