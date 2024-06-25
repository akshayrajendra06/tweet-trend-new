pipeline {
    agent {
        label 'maven'
    }

environment{
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
