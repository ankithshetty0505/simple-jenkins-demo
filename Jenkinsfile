pipline {
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
        sh 'chom +x script.sh'
      }
    }
  }
}
