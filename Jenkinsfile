node('master'){
	checkout scm
	stage('Build'){
		bat 'python test.py'
	}
}