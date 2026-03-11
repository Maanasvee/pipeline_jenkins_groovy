pipeline {
    agent any

    options {
        skipDefaultCheckout(true)
    }

    stages {

        stage('Pull from Git') {
            steps {
                git branch: 'main', url: 'https://github.com/Maanasvee/pipeline_jenkins_groovy.git'
            }
        }

        stage('Build') {
            steps {
                bat '.\\Build.bat'
            }
        }

        stage('Test') {
            steps {
                bat '.\\Test.bat'
            }
        }

        stage('Deploy') {
            steps {
                bat '.\\Deploy.bat'
            }
        }

    }
}
