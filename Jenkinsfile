pipeline {
  agent any
  
  stages {
    
    stage('Clone') {
      steps {
        git url:'https://github.com/ankithshetty0505/simple-jenkins-demo.git',
          branch: 'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
