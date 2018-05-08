pipeline {
agent any 
stages {
stage ('build') {
steps {
withMaven (Maven : ' Maven_3_3_9') {
sh 'mvn clean package'
}
}
}
}
