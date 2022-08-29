pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building' 
                echo 'Building the first section'
                echo '${branch}'
            }
        }
            
        
        stage('Test') {
            steps {
                echo 'Testing'
                echo 'This is testing area'
                echo 'Testing is almost at its end'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
