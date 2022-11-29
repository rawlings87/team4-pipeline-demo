pipeline{
    agent any
    stages{
        stage('1-repoClone'){
            steps{
                sh 'df -h'
            }
        }
        stage('2-cpuAnalysis'){
            steps{ 
                sh 'lscpu'
        }

        }
        stage('3-memoryCheck'){
            steps{
                sh 'free -g'
            }

        }
        stage('4-os-stats'){
            steps{

             'cat /etc/os-release'
        }
    }
}