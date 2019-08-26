pipeline {
	agent any
	
	stages {
		stage ('compile stage') {
			
			steps {
				withMaven(maven : 'maven3.3.3') 
					sh 'mvn clean compile'
				
			}
		}
	}
}
