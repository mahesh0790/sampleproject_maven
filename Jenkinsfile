node {
stage ("scm checkout"){
git "https://github.com/mahesh0790/sampleproject_maven"
}
stage ("maven packaging"){
sh "mvn clean install"
}
  stage ("mail "){
    mail bcc: '', body: 'maheshdeo', cc: '', from: '', replyTo: '', subject: 'mahesh demo', to: 'maheshdevops18@gmail.com'
  }
}
