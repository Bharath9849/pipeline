node('built-in')
    {
           stage('Continuous Download-loans')
	   {
           git 'https://github.com/yankils/hello-world.git'
       }
	       stage('Continuous Build-loans')
	   {
           sh 'mvn package'
       }
    }
