pipeline {
    agent any
    // agent {
    //     docker { image 'node:14-alpine' }
    // }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'set'
            }
        }
        stage('Prod') {
            steps {
                echo 'hoppela'
            }
        }
    }
}
