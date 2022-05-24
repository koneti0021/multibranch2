node('master') 
{
    stage('Continuous Download_test') 
	{
    git 'https://github.com/koneti0021/multibranch2.git'
	}
    stage('Continuous Build_test') 
	{
    sh label: '', script: 'mvn package'
	}
}
