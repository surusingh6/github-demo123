pipeline {
  agent any 
   stages {
     stage ('Checkout') {
       steps {
       checkout scm // Checks out the specific revision that triggered the build
         sh "pwd"
         sh "ls -lrt"
     }
    
  }
}
}
