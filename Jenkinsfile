pipeline {
    agent any
    stages {
        stage('Build Compilation') {
            steps {
                withMaven(jdk: '', maven: 'Maven3.6') {
                  sh 'mvn clean install'

                    }
            }
        }

    }
}
