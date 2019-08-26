pipeline {
	agent any
	
	stages {
		stage ('compile stage') {
			
			steps {
				withMaven(maven : 'maven 3.5.0') 
					sh 'mvn clean compile'
				
			}
		}
	}
}
