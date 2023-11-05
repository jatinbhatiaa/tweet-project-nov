pipeline {
    agent {
        node {
            label 'slave'
            
        }
    }
    stages{
        stage('fetch code'){
            steps {
                git branch: 'main', url: 'https://github.com/jatinbhatiaa/tweet-project-nov.git'
            }
        }
    }
}