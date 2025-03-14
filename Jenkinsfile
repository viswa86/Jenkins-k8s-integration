pipeline {
    agent any  // Runs on any available agent
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/viswa86/Jenkins-k8s-integration.git'  // Replace with your repo
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application... (Placeholder for actual build commands)'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests... (Placeholder for actual test commands)'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application to Kubernetes'
                script {
                    sh 'kubectl apply -f k8s-deployment.yaml'
                }
            }
        }
    }
}
