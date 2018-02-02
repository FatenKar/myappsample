pipeline {
    agent any
    stages{
        stage('Initialize'){
            steps{
                sh'''
                   echo "Path = ${PATH}"
                   echo "M2_HOME = ${M2_HOME}"
                   '''
            }
        }
        stage ('Build'){
            steps{
                echo 'Hello World!'
            }
        }
    }
}
