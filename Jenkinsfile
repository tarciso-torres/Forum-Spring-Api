pipeline {
    agent any
    stages {
        stage ('Build Backend') {
            bat 'mvn clean package -DskipTests=true'
        }
         stage ('Unit Tests') {
            steps {
                bat 'mvn test'
            }
        }
    }
}