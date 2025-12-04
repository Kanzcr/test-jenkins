pipeline {
    agent any

    stages {
        stage('Clean Workspace') {
            steps {
                deleteDir() // hapus semua isi workspace
            }
        }

        stage('Build') {
            steps {
                echo '🔧 Building application...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying application...'
            }
        }
    }
}