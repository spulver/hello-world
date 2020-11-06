pipeline {
    agent {
        docker { image 'node:14-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
    stages {
        stage('Prod') {
            steps {
                echo 'hoppela'
            }
        }
    }
}
