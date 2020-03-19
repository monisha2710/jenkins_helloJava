pipeline{
	agent any
	environment{
		PATH = "C:\\WINDOWS\\SYSTEM32"
	}
	stages{
		stage("Compile"){
			steps{
				bat 'javac HelloWorld.java'
			}
		}
		
		stage("Run"){
			steps{
				bat 'java HelloWorld'
			}
		}
	}
}
