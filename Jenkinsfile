pipeline {
    agent any
    triggers {
        cron('* * * * *')
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