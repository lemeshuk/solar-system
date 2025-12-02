pipeline {
    agent any

    stages {
        stage('VM Node Version') {
            steps {
                sh '''
                    echo "==> Printing the version of Node.js"
                    node -v
                    echo "==> Printing the version of NPM"
                    npm -v
                '''
            }
        }
    }
}