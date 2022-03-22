node('master') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/saitataji/multipipeline.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
