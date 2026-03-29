@Library('jenkins-shared-library') _   // global library name


pipeline {
    agent any

    stages {
        stage('Greet') {
            steps {
                // Call the shared library function
                hello()  
            }
        }
    }
}
