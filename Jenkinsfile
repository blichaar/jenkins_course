pipeline {
    agent any
    environment {
        python = '"C:\\Program Files\\WindowsApps\\PythonSoftwareFoundation.Python.3.13_3.13.496.0_x64__qbz5n2kfra8p0\\python3.13.exe"'
    }
    stages {
        stage('Build') {
            steps {
                bat "${python} code.py"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Scripting') {
            steps {
                echo "Scirpting"
            }
        }
    }
}
