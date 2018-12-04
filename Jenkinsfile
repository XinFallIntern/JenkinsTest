node("Docker"){
    /* Requires the Docker Pipeline plugin to be installed */
    docker.image('hello-world').inside {
        stage('Test') {
            bat "MSBuild"
        }
    }
}
