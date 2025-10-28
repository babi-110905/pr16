pipeline {
    agent any
    stages {
        stage('Build') { steps { bat 'javac CounterApp.java' } }
        stage('Run') { steps { bat 'java CounterApp' } }
    }
}
