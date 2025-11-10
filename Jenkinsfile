@Library('my-shared-lib') _
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