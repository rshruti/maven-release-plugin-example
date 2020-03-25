pipeline{
    agent any
    stages{
        stage('SCM-Checkout'){
            steps{
            git 'https://github.com/rshruti/maven-release-plugin-example.git'
            }
        }
         stage('Build'){
            steps{
                sh '/opt/maven/bin/mvn clean package -Dmaven.test.skip=true'                
            }
        }  
        }
        }
