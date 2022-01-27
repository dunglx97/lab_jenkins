pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sshagent(['remote-ssh']) {
					sh 'ssh -o StrictHostKeyChecking=no -l ubuntu 18.204.218.201 touch dung.txt '
				}
            }
        }
    }
}