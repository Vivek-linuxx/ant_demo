pipeline {
  agent any
  stages {
    stage('Build') {
	    steps {
		    sh 'printenv'
		    sh 'ant -f build.xml -v'
		    }
		}
	  post {
		  always {
			  archive 'dist/*.war'
		  }
	  }
	}	
}
