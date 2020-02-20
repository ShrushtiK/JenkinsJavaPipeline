pipeline {
	agent any
	stages {
		stage('Clone repo'){
			steps {
			 sh "git clone https://github.com/ShrushtiK/JenkinsJavaPipeline"
			}		
		}
		stage('Run'){
			sh "cd JenkinsJavaPipeline"
			sh "sudo javac HelloWorld.java"
			sh "sudo java HelloWorld"
		}
		
	}

}
