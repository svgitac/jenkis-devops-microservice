pipeline {

  agent {  docker { image 'maven:3.6.3' } }



stages {
	stage('Build') {
		echo 'mvn --version'
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}

   stage('Integeration Test') {
		echo "ntegeration Test"
	}

}
