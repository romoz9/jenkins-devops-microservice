pipeline {
	//agent any
	agent { docker { image 'node:16.13.1-alpine'}  } 
	stages {
		stage('Build') {
			steps {
				sh 'node --version'
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}
}