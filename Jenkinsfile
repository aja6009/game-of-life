node {
  
   stage('SCM') {
      // git clone
	  git 'https://github.com/aja6009/game-of-life.git'
	  
   }
   
   stage ('build package') {
      // mvn package
	  sh 'mvn package'
   }
   
   stage ('archival') {
     // archival artifacts
	 archive 'target/*.jar'
   }
   
} 
