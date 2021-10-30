pipeline {	 
    	stages {     	 
    	stage("Compile") {          	 
		agent { node { label 'slave1' } }
            	steps {               	 
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
	}
}

