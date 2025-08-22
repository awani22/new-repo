pipeline {
    agent any

    stages {
        stage('Print Message') {
            steps {
                echo '🚀 Jenkins Pipeline Started!'
                echo "Hello Iqra 👋"
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -l'   // lists files in your repo
            }
        }

        stage('Run a Script') {
            steps {
                sh 'echo "This is where you can run shell commands or scripts"'
            }
        }

        stage('Simulate Build') {
            steps {
                echo '🔨 Compiling code (simulation)...'
                sh 'sleep 2'  // wait for 2 seconds to simulate build
                echo '✅ Build Completed'
            }
        }

        stage('Simulate Test') {
            steps {
                echo '🧪 Running Tests...'
                sh 'echo "All tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚢 Deploying Application...'
                sh 'echo "Application deployed successfully!"'
            }
        }
    }

    post {
        always {
            echo '📌 Pipeline Finished!'
        }
    }
}
