# amisha
pipeline {
    agent any
     stages {
        stage('Build') {
            steps {
                echo 'Hello Peter!'
            }
        }
        stage('Test') {	
            steps {
                echo 'Peter listen to me, you idiot!'
            }
        }
        stage('Deploy 1') {
            steps {
                echo 'mj misses you'
            }
        }
        stage('Deploy 2') {
            steps {
                echo 'Venom gonna come for you'
            }
        }
    }
}



