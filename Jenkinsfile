node('built-in') 
{
    stage('Continuous Download_On_Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_OnMaster') 
	{
    sh label: '', script: 'mvn package'
	}
 }
