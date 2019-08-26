pipeline {
	agent any
	stages {
		stage('Clone Repo') {
			steps {
				sh "ip a"
				sh "sudo su - ec2-user"
				
				sh "curl -o kubectl https://amazon-eks.s3-us-west-2.amazonaws.com/1.13.7/2019-06-11/bin/linux/amd64/kubectl"
				sh "chmod +x ./kubectl"
				sh "./kubectl get nodes"
                                sh "./kubectl deploy nginx.yaml"
        

			}
		}
	}
}
