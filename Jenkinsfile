pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps{
                git branch: 'feature/dev', 
                    url: 'https://github.com/Naresh240/springboot_webhook_trigger.git'
            }
        }
        stage("Build_Artifact") {
            steps {
                sh "mvn clean pakcage"
            }
        }
    }
}
