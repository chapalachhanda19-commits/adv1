pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                chekcout scm
            }
        }
        stage('run the code') {
            steps {
                sh 'python adv1/extract.py'
            }
        }
        
    }   
}