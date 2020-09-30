pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir -p ~/jenkins-tutorial-test"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch -p ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }    
}
