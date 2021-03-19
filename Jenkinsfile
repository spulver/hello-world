pipeline {
    agent any
    // agent {
    //     docker { image 'node:14-alpine' }
    // }
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
