pipeline
{
	agent any
		tools
		{
			maven 'MAVEN_HOME'
		}
		stages
		{
			stage('Welcome Stage')
			{
				steps
				{
					echo 'Welcome to my new Jenkins Pipeline'
				}
			}
			
			stage('Clean Stage')
			{
				steps
				{
					bat 'mvn clean'
				}
			}
			stage('Test Stage')
			{
				steps
				{
					bat 'mvn test'
				}
			}
			
			stage('Build Stage')
			{
				steps
				{
					bat 'mvn install'
				}
			}
			
			stage('Final Success')
			{
				steps
				{
					echo 'Final  build Success'
				}
			}	

			
		}
}
