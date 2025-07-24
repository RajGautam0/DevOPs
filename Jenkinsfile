pipeline {
    agent any
    stages {
        stage('Staging') {
            steps {
                echo 'Running staging environment build...'
                // Put test or dummy deploy logic here
            }
        }

        stage('Approval') {
            steps {
                input message: 'Approve to proceed to Production?'
            }
        }

        stage('Production Build') {
            steps {
                echo 'Running production build...'
                // Put final build/deploy commands here
            }
        }
    }
}
