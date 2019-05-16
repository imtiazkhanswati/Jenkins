node {
checkout scm
  stage('Build'){
    sh 'make'
    archiveArtifacts artifacts: 'C:/Users/c5280174/Desktop/MyProject.jar' , fingerprint: true
echo 'Build success'
  }
  stage('Test sadfsadf'){

echo 'Test success'
}
stage('Deploy'){
echo 'Deploy success'
echo 'Deploy local test'
}
}
