pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sshagent(['remote-ssh']) {
					sh 'ssh -o StrictHostKeyChecking=no -l ubuntu 54.197.201.23 touch dung.txt '
				}
            }
        }
    }
}