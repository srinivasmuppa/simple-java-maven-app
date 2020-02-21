pipeline 
{

  stages
  {
    
    stage ('checkout from git Repo')
     {
      git url: 'https://github.com/srinivasmuppa/simple-java-maven-app/'
     }   
    stage ('compile')
    {
     bat 'mvn package'
    }
  }
}
        
      
