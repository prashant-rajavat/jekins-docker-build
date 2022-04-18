// pipeline {
//   agent any
//   stages {
//     stage('build') {
//       sh "docker build -t docker/getting-started ."
//     }
//   }
// }

pipeline {
  agent any
  stages {
    stage('Building image') {
      steps{
        script {
          sh "docker build -t docker/getting-started ."
        }
      }
    }
  }
}