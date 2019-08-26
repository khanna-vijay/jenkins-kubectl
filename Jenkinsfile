pipeline {
	agent any
	stages {
		stage('Clone Repo') {
			steps {
				sh "ip a"
				sh "./kubectl get nodes"
                                sh "./kubectl deploy nginx.yaml"
        

			}
		}
	}
}
