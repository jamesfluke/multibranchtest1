pipeline {
    agent any

    triggers {
        { pollSCM * * * * * }
    }

    stages {
        stage('Main') {
            steps {
                sh 'echo devbranch!'
            }
        }
    }
}
