pipeline {
        agent any
  triggers {
    cron('*/10 * * * *')
  }
  
  stages {
    stage('Trigger Downstream job'){
      steps {
          build job: 'Downstreamjob'
      } 
     
    }
  }
      
}
