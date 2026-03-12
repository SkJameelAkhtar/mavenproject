// node {
//   stage('cloning maven project')
//   {
//     git 'https://github.com/Sharath-yp25/mavenproject.git'
//   }
//   stage('Building maven project')
//   {
//     sh 'mvn package'
//   }
//   stage('print'){
//     echo "Hi my name is john"
// }
// }
// new line


pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/SkJameelAkhtar/mavenproject.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

    }

}
