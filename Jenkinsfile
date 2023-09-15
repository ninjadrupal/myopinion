pipeline {
  agent any
  stages {
    stage('composer install') {
      steps {
       echo "composer install ${SITE} "
      }
    }

    stage('create artifact') {
      steps {
          echo "create artifact"
      }
    }

    stage('Update database') {
      steps {
        echo "Update database"
      }
    }
  }
}