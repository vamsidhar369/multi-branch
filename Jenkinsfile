node('built-in') 
{
    stage('Continuous Download on m') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build on m') 
	{
    sh label: '', script: 'mvn package'
	}
}
