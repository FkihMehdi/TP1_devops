pipeline {
    agent any

    tools {
        maven 'Maven3'
    }

    stages {

        stage('Build with Maven') {
            steps {
                sh 'mvn clean install'
            }
        }


    }
}