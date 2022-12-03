pipeline {
    agent any
    environment {
        TEAM4 = "variables."
    }
    stages {
        stage("Build") {
            environment {
                TEAM4 = "Testing healthapp."
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
                echo "$Team4healthapp"
            }
        }
        stage("Release") {
            steps {
                echo "Release stage."
                echo "${Team4healthapp}"
            }
        }
    }
}