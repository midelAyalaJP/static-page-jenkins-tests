pipeline {
    agent any

    options {
        timeout(time: 5, unit: 'MINUTES')
    }
    

    stages {
        stage('Testings') {
            steps {
                script {
                    sh'''
                        echo "tests"
                    '''
                }
            }
        }
        stage('Deploy') {
            steps {
                sh '''
                    mv . /home/midelaya/Projects/docker-server-4/apps/app-service/
                '''
                
            }
        }
       
    
    }
}