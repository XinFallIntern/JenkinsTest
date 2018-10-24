node('master'){
	checkout scm
	stage('Build'){
		docker.image('maven:3.3.3').inside{
			bat 'python test.py'
		}
	}
}