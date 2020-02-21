pipeline 
{


    
    stage ('checkout from git Repo')
     {
      git 'https://github.com/srinivasmuppa/simple-java-maven-app.git'
     }   
    stage ('compile')
    {
     bat 'mvn package'
    }
  
}
        
      
