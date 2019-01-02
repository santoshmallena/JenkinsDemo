pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        docker {
          image 'maven:3.6.0'
        }

      }
      steps {
        sh '''#! /bin/sh
echo "Build Started"

mvn --version'''
      }
    }
    stage('') {
      steps {
        sh '''#! /bin/sh

echo "Testing stage started"'''
      }
    }
  }
}