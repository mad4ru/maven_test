pipeline {
	agent any

	stages {
	  stage ('compile stage') {

	    steps {
  	      withMaven(maven : 'maven 3.0.5'){

		sh 'mvn clean compile'


		}
	     }

	  }

          stage ('Testing stage') {

            steps {
              withMaven(maven : 'maven 3.0.5'){

                sh 'mvn clean test'
                }
             }

          }

	 stage ('Deployment stage') {

            steps {
              withMaven(maven : 'maven 3.0.5'){

                sh 'mvn deploy'
                }
             }

          }

}

}
