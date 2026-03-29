pipeline {
    agent any

    stages {

        stage('Clone Check') {
            steps {
                sh 'pwd'
                sh 'ls -l'
            }
        }

        stage('Run Script') {
            steps {
                sh 'bash Jenkins/Jenkinspractice.sh'
            }
        }

        stage('Output') {
            steps {
                sh 'cat app.txt'
            }
        }
    }
}
