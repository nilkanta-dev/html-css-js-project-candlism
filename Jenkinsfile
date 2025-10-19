pipeline {
    agent any
    tools { nodejs 'Node-24.10' }
    stages {
        stage('Check Node Version') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}
