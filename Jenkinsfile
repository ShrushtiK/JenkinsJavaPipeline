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
			sh "cd JenkinsJavaPipeline"
			sh "sudo javac HelloWorld.java"
			sh "sudo java HelloWorld"}
		}
		
	}

}
