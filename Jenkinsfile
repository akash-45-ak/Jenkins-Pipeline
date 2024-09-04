pipeline{
    agent any
    stages {
        stage("Compile"){
            sh 'javac JenkinsCICD.java'
        }

        stage("Run"){
            sh 'java JenkinsCICD'
        }
    }
}