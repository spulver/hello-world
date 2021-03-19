pipeline {
    agent {
        usr/local/bin/docker { image 'node:14-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
        stage('Prod') {
            steps {
                echo 'hoppela'
            }
        }
    }
}
