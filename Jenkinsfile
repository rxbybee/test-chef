// Jenkinsfile
@Library('hello')
library identifier: 'hello@master', retriever: modernSCM(
  [$class: 'GitSCMSource',
   remote: 'https://github.com/rxbybee/shared_libraries',
   apiKey: 'df4ef0602e6f8bdc885638458df64576cc1947b1'])_

stage('Say Hello') {
  echo 'Hello World'
  sayHello 'shared library!'
}