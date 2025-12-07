pipeline {
    agent any

    tools {
        maven 'M2_HOME'
    }

    stages {
        stage('MAVEN') {
            steps {
                sh 'mvn -version'
                // plus tard tu pourras mettre : sh 'mvn clean install'
            }
        }
    }
}
