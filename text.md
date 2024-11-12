stage('Checkout') {
  steps {
      git url: 'https://github.com/luis12007/Todo_test_aws_jenkins.git', branch: 'master'
  }
}
