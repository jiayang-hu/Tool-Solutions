pipeline {
  agent any
  stages {
    stage('Test Env') {
      steps {
        sh 'ls ~'
        script {
          def script = load "~/arm-tool-solutions-resource/jenkinsTests.Groovy "
          script.run_tests()
        }

      }
    }
  }
}