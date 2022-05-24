node('master') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/koneti0021/multibranch2.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
