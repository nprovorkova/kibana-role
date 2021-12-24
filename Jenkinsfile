pipeline {
  agent any
  stages {
  stage ('Echo') {
      steps {
        echo 'M'
      }
    }
    stage ('Molecule test') {
      steps {
        molecule test
      }
    }
  }
}