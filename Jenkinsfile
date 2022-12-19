pipeline {
	agent any
	tools {
	   maven 'maven'
	} 
	stages {
	   stage("build jar") {
	      steps {
	         
	         sh 'mvn clean install'
	      }
        }
	  
	}
}
