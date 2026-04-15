pipeline {
    agent any

    tools {
        maven 'MyMaven'
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/vikiccha2105-cpu/MyMavenWeApp.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
