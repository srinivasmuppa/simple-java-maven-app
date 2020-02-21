pipeline 
{

  stages
  {
    
    stage ('checkout from git Repo')
     {
      git 'git@github.com:srinivasmuppa/simple-java-maven-app.git'
     }   
    stage ('compile')
    {
     bat 'mvn package'
    }
  }
}
        
      
