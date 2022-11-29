pipeline{
    agent any{
        stage('1-repoClone'){
            steps{
                sh'df -h'
            }
        }
        stage('2-cpuAnalysis'){
            stepssh 'lscpu'
        }
        stage('3-memoryCheck'){
            steps{
                sh 'free -g'
            }

        }
        stage('4-os-stats'){
            stepssh 'cat /etc/os-release'
        }
    }
}