pipeline{
    agent none
    stages{
                stage('Validate'){
                    agent{ label: label1 }
            steps{
                sh 'sleep 5'
                echo 'Validate'
            }
        }
        stage('Compile'){
            agent{ label: label1 }
            steps{
                sh 'sleep 5'
                echo 'compile'
            }
        }
        stage('test'){
            agent{ label: label2 }
            steps{
                sh 'sleep 5'
                echo 'test'
            }
        }
        stage('package'){
            agent{ label: label2 }
            steps{
                sh 'sleep 5'
                echo 'package'
            }
}
         stage('verify'){
             agent{ label: label1 }
            steps{
                sh 'sleep 5'
                echo 'verify'
            }
}
        stage('install'){
            agent{ label: label2 }
            steps{
                sh 'sleep 5'
                echo 'install'
            }
        }
        stage('deploy'){
            agent{ label: label2 }
            steps{
                sh 'sleep 5'
                echo 'deploy'
            }
        }
    }
}
