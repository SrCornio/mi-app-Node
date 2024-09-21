pipeline {
    agent any
    stages {
        stage('Compilar') {
            steps {
                script {
                    sh 'npm install'
                }
            }
        }
        stage('Pruebas') {
            steps {
                script {
                    sh 'npm test'
                }
            }
        }
        stage('Despliegue') {
            steps {
                echo 'Despliegue exitoso.'
            }
        }
    }
}
