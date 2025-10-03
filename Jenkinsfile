node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/divyarajprankur/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	
	}
}

