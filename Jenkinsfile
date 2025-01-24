pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Scripting') {
            steps {
                parallel {
                    "TaskOne" :{
                        echo "task one stuff 1"
                        echo "task one stuff 2"
                        echo "task one stuff 3"
                    },
                    "TaskTwo" :{
                        echo "task two stuff 1"
                        echo "task two stuff 2"
                    }
                }
            }
        }
    }
}
