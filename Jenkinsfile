pipeline {
   agent { docker { image 'python:3.7.2' } }
  stages {
    stage('build') {
      steps {
         python app.py
      }
    }
    stage('test') {
      steps {
        echo "nothing"
      }
    }
  }
}
