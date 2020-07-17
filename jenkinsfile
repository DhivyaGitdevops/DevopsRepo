pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh mvn clean -f DevopsRepo
            }
        }
    stage('Test') {
            steps {
                sh mvn test -f DevopsRepo
            }
        }
    stage('Test') {
            steps {
                sh mvn package -f DevopsRepo
            }
        }
    }
}
