node('master') 
{
    stage('Continuous Download_test') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_test') 
	{
    sh label: '', script: 'mvn package'
	}
}
