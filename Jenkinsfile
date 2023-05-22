pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out the source code from the repository
                git 'git@github.com:deepu2899/SnapShot.git'
            }
        }
        stage('Build') {
            steps {
                // Build the snapshot
               sh 'npm install && npm run build'
            }
        }
    }
}
