pipeline {
	agent any
	stages {
		stage('Build'){
			withMaven(
				maven: 'maven'
				)
			steps{
				sh 'mvn -v'
			}
		}
	}
}
