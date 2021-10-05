pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build quietPeriod: 5, job: 'testjob'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }        
    }
}
