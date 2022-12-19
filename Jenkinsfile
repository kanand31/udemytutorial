pipeline {
	agent { label "jenkinsslave" }
	tools { maven "M2_HOME" jdk "JAVA_HOME" }
	stages {
	   stage("build"){
	      steps {
	         sh "mvn clean install"
	      }
        }
	  
	}
}
