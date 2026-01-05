pipeline {
	agent any
	stages {
		stage('GitHub'){
			steps {
				git branch: 'main', url: 'https://github.com/fuekeng/jenkins-pipeline.git'
			}
		}
	}
}