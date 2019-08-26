pipeline {
	agent any
	
	stages {
		stage ('compile stage') {
			
			steps {
				tool name: 'maven 3.6.0', type: 'maven'
					sh 'mvn clean compile install package'
				
			}
		}
	}
}
