pipeline{ 

  agent any  

  tools{
    
  }

  stages{
    stage('build'){
      steps{
        sh 'mvn compile'
      }
    }

    stage('test'){
      steps{
        sh 'mvn clean test'        
      }
    }

    stage('pkg'){
      steps{
        sh 'mvn package -DskipTests'  
      }
    }


  }
}
