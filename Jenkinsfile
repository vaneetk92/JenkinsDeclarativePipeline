pipeline 
{
    agent any
    stages 
{
        stage('Build') 
	{
            steps 
		{
               echo "Building the project........."
		bat "mvn clean"		
           	 }
	}
		stage('Test') 
		{
            steps 
			{
               echo "testing the project........."
		bat "mvn test"	
            }
	}
        stage('deploy') 
		{
            steps 
		{
               echo "Deploying the project........."
		bat "mvn compile"			
        	 }
   	}
		stage('Release') 
		{
            steps 
			{
               echo "releasing the Project///////"
            }	
            
        }
}
}
