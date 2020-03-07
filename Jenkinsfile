pipeline
{
    environment {
        PATH = "/opt/apache-maven-3.6.3/bin:$PATH"
    }
    agent {
        label 'node1'
        }
        stages{
            stage('checkout')
            { 
                steps{
                   git 'https://github.com/srinivasmuppa/simple-java-maven-app.git'
                    }
            }
            stage('build')
            {
                steps{
                    sh 'mvn clean package'
                    }
            }
            stage('deploy')
            {
                steps{
                    sh 'cp /root/workspace/demobuildcopy/target/*.jar /tmp'

                }
            }

        }
 }
