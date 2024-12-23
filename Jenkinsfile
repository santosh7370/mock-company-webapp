pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // TODO: Add build command
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // TODO: Add test command
                sh './gradlew test'
            }
        }
    }
}
