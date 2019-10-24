pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                mvn compile
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                mvn package
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}