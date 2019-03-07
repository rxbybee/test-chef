// Jenkinsfile
library identifier: 'hello@master', retriever: modernSCM(
  [$class: 'GitSCMSource',
   remote: 'https://github.com/rxbybee/shared_libraries.git',
   credentialsId: 'rxbybee'])_

stage('Say Hello') {
  echo 'Hello World,'
  sayHello 'shared library!'
}