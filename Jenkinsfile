// Jenkinsfile
@Library('hello')
library identifier: 'hello@master', retriever: modernSCM(
  [$class: 'GitSCMSource',
   remote: 'https://github.com/rxbybee/shared_libraries',
   apiKey: '{GIT_AUTH_KEY}'])_

stage('Say Hello') {
  echo 'Hello World'
  sayHello 'shared library!'
}