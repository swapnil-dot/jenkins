pipeline {
    agent {
        docker { image 'swapy25/javaimage:1.0' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java --version'
            }
        }
    }
}
