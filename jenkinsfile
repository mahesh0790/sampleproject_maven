node {
stage ("scm checkout"){
git "https://github.com/mahesh0790/sampleproject_maven"
}
stage ("maven packaging"){
sh "mvn clean install"
}
}
