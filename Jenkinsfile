pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    stages {
       stage ('Build') {
            steps {
                bat 'mvn -Dmaven.test.failure.ignore=true compile test' 
            }
        }
    }
}
