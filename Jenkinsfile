pipeline { 
     agent any
  stages {
    stage ('git checkout'){
         steps{
    git "https://github.com/mahesh0790/sampleproject_maven.git"
    }
         steps{
         sh 'mvn clean install'
         }
         
    }
  }
  
}
