pipeline {	 
	agent none
    	stages {     	 
    	stage("Compile") {          	 
		agent { node { label 'slave1' } }
            	steps {               	 
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Test") {          	 
		agent { node { label 'slave2' } }
            	steps {               	 
                	sh "mvn test"          	 
            	}     	 
        	}     	 
	}
}

