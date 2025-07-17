pipeline {
    agent Test

    stages {
        stage('Build') {
            steps {
                echo "🔧 Build stage started"
                sh '''
                    echo "Compiling source code..."
                    # Simulate build process
                    sleep 2
                    echo "Build completed."
                '''
            }
        }

        stage('Test') {
            steps {
                echo "🧪 Test stage started"
                sh '''
                    echo "Running unit tests..."
                    # Simulate test process
                    sleep 2
                    echo "All tests passed."
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo "🚀 Deploy stage started"
                sh '''
                    echo "Deploying applied."
                '''
            }
         }
         }
}



