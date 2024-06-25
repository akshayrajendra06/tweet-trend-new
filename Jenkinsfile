pipeline {
    agent {
        label 'maven'
    }

enviroment{
    PATH ="/opt/apache-maven-3.9.8/bin:$PATH"
}
    stages {
        stage('Clone-code') {
            steps {
               sh 'mvn clean deploy'
            
         }
        }
    }
}
