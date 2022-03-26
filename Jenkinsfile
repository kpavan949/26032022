pipeline {
    agent any 
    stages{
        stage ('GIT') {
            step {
                git branch: 'main', url: 'https://github.com/kpavan949/26032022.git'
            }
        }
        
       stage ('BUILED') {
            step {
                sh '''mvn clean package
'''
            }
        } 
    }
}
