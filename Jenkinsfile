pipeline {
     agent any
     stages{
     stage ('scm checkout'){
          steps{
          git "https://github.com/mahesh0790/sampleproject_maven.git"
}
     }
     stage ('mvn packaging'){
          steps{
     sh 'mvn clean install'
     }
}
     }
}

