pipeline {
    agent any

    stages {
        stage('compile') {
            steps {

                echo 'compiling..'
				sh 'mvn clean compile'
				echo 'Compiled successfully'
            }
        }
        stage('Packaging') {
            steps {
                echo 'packaging..'
				sh 'mvn clean package'
				echo 'packaged successfully'

            }
        }
        stage('test') {
            steps {
                echo 'Deploying....'
            }
        }
		stage('Stagging deployement') {
            steps {
                echo 'Deploying....'
				sh 'java -version'
            }
        }
		stage('Prod deployement') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}