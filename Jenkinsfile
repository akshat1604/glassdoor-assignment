pipeline {
    agent any
    triggers {
        cron('H * * * *')
    }
    stages {
        stage('Build') {
            steps {
                sh '''
                echo "Environment Variables:"
                printenv
                '''
            }
        }
    }
}