pipeline {
  agent any
  stages {
    stage('Build') {
	    steps {
		    sh 'printenv'
		    sh 'ant -f build.xml -v'
		    }
		}
    stage ('post-build') {
	  steps {
		  archive 'dist/*.war'
	  }
    	}
	}	
}
