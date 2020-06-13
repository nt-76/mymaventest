pipeline {
    agent any
    stages {
        stage('Build Compilation') {
            steps {
                withmaven(maven : 'maven_3_6_3'){
                sh 'mvn clean install'
                }
            }
        }
         stage('Build Test') {
                    steps {
                        withmaven(maven : 'maven_3_6_3'){
                            sh 'Build TestING'
                            }
                    }
                }
    }
}
