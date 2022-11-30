pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola"
                
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola mundo"
                '''
            }
        }
            stage('testing') {
            steps {
                sh '''
                echo "tareas de testing"
                '''
            }
         }
        stage('deployar') {
            steps {
                sh '''
                echo "hola mundo"
                '''
            }
        }
    }
}
