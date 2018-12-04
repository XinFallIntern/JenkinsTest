node("Docker"){
	checkout scm
    /* Requires the Docker Pipeline plugin to be installed */
    docker.image('slaveimage').inside {
        stage('Test') {
            bat "MSBuild"
        }
    }
}
