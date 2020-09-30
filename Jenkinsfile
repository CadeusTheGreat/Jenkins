pipeline{
        agent any
        stages{
                if (not filexists '~/jenkins-tutorial-test'){
                    stage('Make Directory'){
                        steps{
                            sh "mkdir ~/jenkins-tutorial-test"
                        }
                    }
                    stage('Make Files'){
                        steps{
                            sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                        }
                    }
              }
        }    
}
