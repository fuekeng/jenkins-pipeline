pipeline {
	agent any
	tools {
		nodejs 'NodeJS'
	}
	stages {  
		stage('GitHub'){
			steps {
				git branch: 'main', url: 'https://github.com/fuekeng/jenkins-pipeline.git'
			}
		}

		stage('Unit Test'){
			steps {
				sh 'npm test'
				sh 'npm install'	
			}
		}



	}
}