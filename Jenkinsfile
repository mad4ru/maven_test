pipeline {
	agent any

	stages {
	  stage ('compile stage') {

	    steps {

		sh 'ls -lhrt'


		}

	  }

          stage ('Testing stage') {

            steps {

                sh 'mvn --version'
                }

          }

	 stage ('Deployment stage') {

            steps {

                sh 'date'
                }

          }

}

}
