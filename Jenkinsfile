node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/PoornimaAnand21/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
