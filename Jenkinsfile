pipeline { 
    docker
    stages {
        stage('Clone') { 
            steps { 
                sh '/stages/01_clone.sh'
            }
        }
        stage('Build') { 
            steps { 
                sh '/stages/02_build.sh'
            }
        }
    }
}