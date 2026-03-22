pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                echo '🚀 Pipeline started...'
            }
        }

        stage('Build') {
            steps {
                echo '🔨 Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '📦 Deploying application...'
            }
        }
    }

    post {
        always {
            echo '✅ Pipeline execution completed.'
        }
        success {
            echo '🎉 Pipeline succeeded!'
        }
        failure {
            echo '❌ Pipeline failed.'
        }
    }
}
