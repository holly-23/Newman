
pipeline{
  agent any
  
  stages {
    stage("build") {
      steps {
        echo 'building the application...'
      }
      
    }
    stage("test") {
      steps {
        echo 'testing the application...'
        readJSON file: 'amazon_complete.postman_collection.json'
      }
      
    } 
    stage("deploy") {
      steps {
        echo 'deploying the application...'
      }
      
    } 
  }
}
