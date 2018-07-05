node {
stage ("scm checkout"){
git "https://github.com/mahesh0790/sampleproject_maven"
}
stage ("maven packaging"){
sh "mvn clean install"
}
  stage ("docker image build"){
    sh "sudo docker build -t 'mahesh0790/demo' ."
  }
}
