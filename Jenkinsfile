@Library('jenkins-shared-library') _
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