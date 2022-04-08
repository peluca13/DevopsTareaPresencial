pipeline {
    agent any
    
    stages {
        stage('Verify code') {
            steps {
                echo 'Validando codigo'
            }
        }
    
    stages {
        stage('Build') {
            steps {
                echo 'Generando codigo....'
            }
        }
        stage('Test') {
            steps {
                echo 'Testeando aplicacion...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Subiendo a ambientes...'
            }
        }
    }
}
