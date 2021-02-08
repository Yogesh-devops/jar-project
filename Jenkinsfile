pipeline {
	agent any 
       stages {
	   
	   stage('SCM'){
	    steps {
				git branch: 'main', changelog: false, poll: false, url: 'https://github.com/awspandian/jar-project.git'
		}
}
	stage('BUILD'){
	    steps {	
				sh 'mvn clean'

}				
}
}
}
