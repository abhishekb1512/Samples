pipeline {
  agent any
  stages {
    stage('Fetch Dates') {
      steps {
        sh 'echo 1 '
      }
    }

    stage('Batch 1') {
      parallel {
        stage('1.11 - PRE') {
          steps {
            sh 'echo 2 '
          }
        }

        stage('6.5 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

        stage('1.34 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

        stage('6.2 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

        stage('I_241') {
          steps {
            sh 'echo 1 '
          }
        }

      }
    }

    stage('Batch 2') {
      parallel {
        stage('1.22 - Clienti bundle IPTV') {
          steps {
            sh 'echo 1'
          }
        }

        stage('1.22 - Annual') {
          steps {
            sh 'echo 1 '
          }
        }

        stage('2.11 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

        stage('6.2.1 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

        stage('I_244') {
          steps {
            sh 'echo I_244'
          }
        }

        stage('1.27 - PRE') {
          steps {
            sh 'echo 1.27'
          }
        }

      }
    }

    stage('Batch 3') {
      parallel {
        stage('6.1 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

        stage('Estrazione contratti con pending') {
          steps {
            sh 'echo 1'
          }
        }

        stage('1.36 - PRE') {
          steps {
            sh 'echo 1'
          }
        }

      }
    }

    stage('Batch 4') {
      parallel {
        stage('I_237 Quadr_Formato_Elettronico') {
          steps {
            sh 'echo 1'
          }
        }

        stage('6.1.2 (ex6.1 old - PRE)') {
          steps {
            sh 'echo 1'
          }
        }

        stage('I_103') {
          steps {
            sh 'echo I_103'
          }
        }

        stage('1.17.1 ') {
          steps {
            sh 'echo 1.17.1'
          }
        }

      }
    }

    stage('Finish') {
      steps {
        echo 'Finish'
      }
    }

  }
}