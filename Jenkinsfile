pipeline{
    agent any
    tools{
        maven 'local_maven'
    }

    stages{
        stage('Build'){
            steps{
                sh 'mvn clean package'

            }

        }
        stage('Deploy to Tomcat Server'){
            steps{
                
            }

        }
    }
}