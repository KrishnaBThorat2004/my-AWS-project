pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/KrishnaBThorat2004/my-AWS-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Success 🚀'
            }
        }
    }
}
