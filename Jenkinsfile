node('master'){
	checkout scm
	stage('Build'){
		docker.inside{
			bat 'python test.py'
		}
	}
}