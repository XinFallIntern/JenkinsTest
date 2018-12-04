pipeline {
    agent "Docker"
        agent { dockerfile true }
            stages {
                stage('Test') {
                    steps {
                        bat 'MSBuild'
                     }
            }
        }
    
}
