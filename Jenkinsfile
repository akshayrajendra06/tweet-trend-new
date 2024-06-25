pipeline {
    agent {
        label 'maven'
    }

    stages {
        stage('Clone-code') {
            steps {
               git branch: 'main', url: 'https://github.com/akshayrajendra06/tweet-trend-new.git'
            }
        }
    }
}
