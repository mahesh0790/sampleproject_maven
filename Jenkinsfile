node {
stage ('git checkout') {
git "https://github.com/mahesh0790/sampleproject_maven.git"
}
stage ('mvn packageing'){
sh 'mvn clean install'
}
}
