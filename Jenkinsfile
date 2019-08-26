pipeline {
	agent any
	stages {
		stage('Clone Repo') {
			steps {
				sh "ip a"
				sh "pwd"
				sh "echo $PATH"
				sh "whoami"
				sh "kubectl get nodes"
                                sh "kubectl deploy nginx.yaml"
        

			}
		}
	}
}
