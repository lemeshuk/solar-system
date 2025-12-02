pipeline {
    agent any

    stages {
        stage('VM Node Version') {
            steps {
                sh '''
                    # Printing the version of node
                    node -v
                    # Printing the version of NPM
                    npm -v
                '''
            }
        }
    }
}