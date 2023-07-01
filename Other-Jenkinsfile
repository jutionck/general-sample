pipeline {
    agent any
    stages {
        stage('Welcome') {
            steps {
                echo 'Welcome...'
                sh 'cat welcome.txt'
            }
        }
        stage('Clone') {
            steps {
                echo 'Clone step'
            }
        }
        stage('Build') {
            steps {
                echo 'Build step'
            }
        }
        stage('Test') {
            steps {
                echo 'Test step'
            }
        }
    }
}