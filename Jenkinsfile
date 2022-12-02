pipeline {
    agent any
    environment {
        TEAM4 = "Test global ENV variables."
    }
    stages {
        stage("Build") {
            environment {
                TEAM4 = "Test stage ENV variables."
            }
            steps {
                echo "Build stage."
                echo "$Ken"
                echo "$Taiwo"
                echo "Pretei"
            }
        }
        stage("Test") {
            steps {
                echo "Test stage."
                echo "$env.SAMPLE_GLOBAL_ENV_VAR"
            }
        }
        stage("Release") {
            steps {
                echo "Release stage."
                echo "${WELCOME TO Team4healthapp}"
            }
        }
    }
}