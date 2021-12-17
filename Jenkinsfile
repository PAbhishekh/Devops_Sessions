pipeline {
  agent any
  stages {
    stage('s1') {
      agent any
      steps {
        sh '''sh \'\'\'
           echo \'this is from build1\'
    \'\'\'
'''
      }
    }

    stage('s2') {
      agent any
      steps {
        echo 'this is from stage2'
      }
    }

  }
}