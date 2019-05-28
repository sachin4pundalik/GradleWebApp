pipeline {
    agent any

    stages {
      stage ('Checkout/Update SCM') {
	steps {
		bat 'gradle assemble --info'
	}
      }
    }	    
}
