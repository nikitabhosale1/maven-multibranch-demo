pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
<<<<<<< HEAD
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
=======

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

>>>>>>> 687c63f3e6cbd06826c4c25c9c38cd5cdb9d6089
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
<<<<<<< HEAD
=======

>>>>>>> 687c63f3e6cbd06826c4c25c9c38cd5cdb9d6089
