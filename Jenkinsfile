pipeline{
    agent any
    stages {
        stage("Compile"){
            steps{
                sh 'javac JenkinsCICD.java'
            }
        }

        stage("Run"){
            steps{
                sh 'java JenkinsCICD'
            }
        }
    }
}