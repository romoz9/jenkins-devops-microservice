pipeline {
	//agent any
	agent { docker {
		alwaysPull true
		image 'maven:3.8.4'}  } 
	stages {
		stage('Build') {
			steps {
				
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