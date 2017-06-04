pipeline {
  	agent {
        label 'master'
    }

    stages {
    	stage('build') {
    		sh 'ant -f build.xml -v'
    	}
    }

    post {
    	always {
    		arhive 'dist/*.jar'
    	}
    }

}

