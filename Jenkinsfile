pipeline {

    agent any
    tools {
        gradle 'Gradle-2.4' 
    }
    stages {
        stage('build stage') {
            steps {
                sh "gradle build" 
        }
    }
