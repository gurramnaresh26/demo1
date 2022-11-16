pipeline{
     	  agent
    		{
    		 label "slave"
		}
    tools{
    	 	maven "m1"
    	}
    stages {
        
        stage('clone') {
            steps{
            git 'https://github.com/Apuroopa4/demo1.git'
        }
        }
    }
}
