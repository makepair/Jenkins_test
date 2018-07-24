pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
		sh 'cp /home/danny/workspace/aa.txt /home/danny/workspace/bb.txt'
            }
        }
    }
}
