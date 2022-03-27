pipeline {
    agent any
    stages{
        stage ('GIT') {
            step {
            script {
                git branch: 'main', url: 'https://github.com/kpavan949/26032022.git'
            }
        }

       stage ('BUILED') {
            step {
            script {
                sh '''mvn clean package
'''
            }
        }
    }
}
