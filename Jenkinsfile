pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                script {
                    if (isUnix()) {
                        sh 'echo using shell within Jenkinsfile'
                    } else {
                        bat 'echo using batch within Jenkinsfile'
                    }
                }
                echo 'Jenkins uses above platform'
            }
        }
        stage('Publish Test Results') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                script {
                    if (isUnix()) {
                        sh 'echo using shell within Jenkinsfile'
                    } else {
                        bat 'echo using batch within Jenkinsfile'
                    }
                }
                echo 'Jenkins uses above platform'
            }
        }
    }
}
