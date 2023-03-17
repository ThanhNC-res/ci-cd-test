/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker pull image 'python:3.9'  }
    stages {
        stage('build') {
            steps {
                echo 'Hello Thanh'
            }
        }
    }
}
