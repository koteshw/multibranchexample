pipeline {

  agent any

  options {

    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')

  }

  stages {
  
      stage('Hello test1 new branch created updated token') {

      steps {

        sh '''

          java -version

        '''

      }

    }

  }

}
