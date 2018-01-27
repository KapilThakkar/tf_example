pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(poll: true, changelog: true, url: 'git@github.com:KapilThakkar/tf_example.git', branch: 'master', credentialsId: 'e3f32e43-99d9-4280-acc4-1f1eeb364f07')
      }
    }
  }
}
