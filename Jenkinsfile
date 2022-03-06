node('master') 
{
    stage('Continuous Download on l') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build on l') 
	{
    sh label: '', script: 'mvn package'
	}
}
