#!groovy
pipeline {
    agent none
   stages {
    stage('Maven Install') {
      agent {
       docker {
         image 'maven:3.9.6-jdk-17'
     }
  }
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }
