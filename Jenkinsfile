pipeline {
  agent any

  stages {
    stage (Compile) {
      steps {
        sh 'echo "This Compiled"'
      }  
    }
    stage(Build) {
      steps {
        echo "Building 1"
	echo "Building 2"
      }
    }
    stage(Testing) {
      steps {
        sh 'echo "Test Babe"'
      }
    }
  }
} 


