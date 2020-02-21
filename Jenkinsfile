pipeline 
{ agent any
   stages
   {
   
		stage('checkout and Build')
		{
			steps
			{
				git 'https://github.com/srinivasmuppa/simple-java-maven-app.git'
				bat 'mvn package'
			}   
		
		}
	}
}
