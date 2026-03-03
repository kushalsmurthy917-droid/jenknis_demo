pipeline {
  agent any
  stages{
    
  stage('Clone'){
    steps{
      git url: 'https://github.com/kushalsmurthy917-droid/jenknis_demo.git',
        branch: 'main'
    }
  }
  stage('Run Script'){
    steps{
      sh 'chmod +x script.sh'
      sh './script.sh'
    }
  }
}
}
