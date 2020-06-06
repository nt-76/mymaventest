pipeline {
    agent any
    stages {
        stage('Build Compilation') {
            steps {
                withmaven(maven : 'maven_3_6_3'){
                sh '/Users/nthumu/Downloads/apache-maven-3.6.3/bin clean install'
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
