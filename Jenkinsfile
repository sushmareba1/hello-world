pipeline {
    agent {
        label 'Test'   // This makes the pipeline run on the agent with label 'test'
    }

    stages {
        stage('Build') {
            steps {
                echo '🔧 Starting Build Stage...'
                sh '''
                    echo "Compiling the code..."
                    sleep 2
                    echo "Build completed."
                '''
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running Tests...'
                sh '''
                    echo "Running unit tests..."
                    sleep 2
                    echo "Tests passed!"
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying Application...'
                sh '''
                    echo "Deploying to staging environment..."
                    sleep 2
                    echo "Deployment successful."
                '''
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline completed successfully.'
        }
        failure {
            echo '❌ Pipeline failed.'
        }
    }
}
