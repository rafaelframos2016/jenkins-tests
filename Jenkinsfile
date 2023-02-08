/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        docker { 
            image 'maven'
             alwaysPull true
             } 
          }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

