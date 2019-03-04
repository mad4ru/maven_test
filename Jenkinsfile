pipeline {
	agent any

	stages {
	  stage ('compile stage') {

	    steps {
  	      withMaven(maven : 'maven 3.0.5'){

		sh 'ls -lhrt'


		}
	     }

	  }

          stage ('Testing stage') {

            steps {
              withMaven(maven : 'maven 3.0.5'){

                sh 'mvn --version'
                }
             }

          }

	 stage ('Deployment stage') {

            steps {
              withMaven(maven : 'maven 3.0.5'){

                sh 'date'
                }
             }

          }

}

}
