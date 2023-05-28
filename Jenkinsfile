pipeline {
  agent { label 'chaitanya' }
  stages {
    stage('build') {
	  steps{
	    git url: "https://github.com/chaitanyasagile/elsaaanaolaf.git",
		  branch: 'devv'
	  }
	}
	stage('develop') {
	  steps{
	    sh "./mvnw package"
	  }
	}
  }
}
