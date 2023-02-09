pipeline {
    agent any

    triggers {
        pollSCM('* * * * *') 
    }

    stages {
        stage('Main') {
            steps {
                sh 'echo devbranch!'
                sh 'echo testing pollSCM'
                sh 'echo testing while disabled.'
            }
        }
    }
}
