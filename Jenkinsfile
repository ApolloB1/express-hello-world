pipeline {
  agent any
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/ApolloB1/express-hello-world.git'
      }
    }
        
    stage('Install ahmed') {
      steps {
        sh 'npm install'
      }
    }  

    stage('apollo') {
      steps {
        echo 'this is apollo branch!'
      }
    }
  }
}
