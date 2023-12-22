pipeline{
    agent none
    stages{
                stage('Validate'){
                    agent { label 'lokesh' }
            steps{
                sh 'sleep 5'
                echo 'Validate'
            }
        }
        stage('Compile'){
            agent { label 'lokesh' }
            steps{
                sh 'sleep 5'
                echo 'compile'
            }
        }
        stage('test'){
            agent { label 'lokesh' }
            steps{
                sh 'sleep 5'
                echo 'test'
            }
        }
        stage('package'){
            agent { label 'lokesh' }
            steps{
                sh 'sleep 5'
                echo 'package'
            }
}
         stage('verify'){
             agent { label 'lokesh' }
            steps{
                sh 'sleep 5'
                echo 'verify'
            }
}
        stage('install'){
            agent { label 'manju' }
            steps{
                sh 'sleep 5'
                echo 'install'
            }
        }
        stage('deploy'){
            agent { label 'manju' }
            steps{
                sh 'sleep 5'
                echo 'deploy'
            }
        }
    }
}
