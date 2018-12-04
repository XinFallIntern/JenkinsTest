pipeline {
        agent {"Docker" dockerfile true }
            stages {
                stage('Test') {
                    steps {
                        bat 'MSBuild'
                     }
            }
        }
    
}
