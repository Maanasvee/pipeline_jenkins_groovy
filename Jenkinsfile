<<<<<<< HEAD

=======
pipeline {
    agent any

    stages {

        stage('Pull from Git') {
            steps {
                git 'https://github.com/Maanasvee/pipeline_jenkins_groovy.git'
            }
        }

        stage('Build') {
            steps {
                bat 'Build.bat'
            }
        }

        stage('Test') {
            steps {
                bat 'Test.bat'
            }
        }

        stage('Deploy') {
            steps {
                bat 'Deploy.bat'
            }
        }

    }
}
>>>>>>> 7c6baaaf7eaf82b6b9b1725ceedf4f644a9add26
