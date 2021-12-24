pipeline {
  agent any
  stages {
    stage ('Molecule test') {
      steps {
        sh 'mkdir -p molecule/default/roles'
        sh 'ln -s \'../../..\' molecule/default/roles/kibana-role'
        sh 'molecule test'
      }
    }
  }
}