pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps{
                git branch: 'main', 
                    url: 'https://github.com/Naresh240/springboot_webhook_trigger.git'
            }
        }
        stage("Build_Artifact") {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
