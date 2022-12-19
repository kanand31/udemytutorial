pipeline {
	agent { label "jenkinsslave" }
	stages {
	   stage("build"){
	      steps {
	         sh "mvn clean install"
	      }
          }
	  
	}
}
