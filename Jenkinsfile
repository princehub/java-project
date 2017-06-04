pipeline {
  	agent {
        label 'master'
    }

    stages {
    	stage('build') {
    		sh 'ant -f build.xml -f'
    	}
    }

}
