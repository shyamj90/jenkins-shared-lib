@Library('jenkins-share-library') _
pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                deployapp(appName: 'MyService', env: 'staging')
            }
        }
    }
}