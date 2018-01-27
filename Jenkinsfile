pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(poll: true, changelog: true, url: 'git@github.com:KapilThakkar/tf_example.git', branch: 'master', credentialsId: 'bac9481f-710b-40b9-abd6-49d3035f191b')
      }
    }
  }
}
