pipeline {
    agent {label 'dev'}
    tools {tool 'maven'}
    stages {
        stage('git') {
            steps {
                git 'https://github.com/Nithinshetty41/dicet_tv.git'
            }
        }
        stage('build') {
            steps {
            sh 'mvn clean package'
            }
        }
    }
}

