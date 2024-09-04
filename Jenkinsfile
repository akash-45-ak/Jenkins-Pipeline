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

    post{
        always{
            sh 'echo "Runs Always"'
        }

        success{
            sh 'echo "Build Success"'
        }

        failure{
            sh 'echo "Build Failed"'
        }
    }
}