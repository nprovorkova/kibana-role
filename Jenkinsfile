pipeline {
  agent any
  stages {
    stage ('Molecule test') {
      steps {
        sh 'mkdir -p molecule/default/roles'
        sh 'ln -sf `pwd` molecule/default/roles/kibana-role'
        sh 'molecule test'
      }
    }
  }
}