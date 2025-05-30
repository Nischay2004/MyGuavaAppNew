pipeline {
	agent any
	
	tools {
		maven 'Maven'
		jdk 'JDK'
	}
	stages{
		stage('Checkout') {
			steps {
				git 'https://github.com/Nischay2004/MyGuavaAppNew.git'
			}
		}
		stage('Build') {
			steps {
				sh 'mvn clean install'
			}
		}
	}
}
