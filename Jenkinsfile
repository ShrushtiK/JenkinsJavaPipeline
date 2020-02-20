pipeline {
	agent any
	stages {
		stage('Clone repo'){
			steps {
			 sh "echo 'CLONING OVER'"
			}		
		}
		stage('Run'){
			steps{
			sh "sudo javac HelloWorld.java"
			sh "sudo java HelloWorld"}
		}
		
	}

}
