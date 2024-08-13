pipeline
       {
        agent any
            stages
                 {
                 stage("Git")
                      {
                      steps
                        {
                        git "https://github.com/kmc-1234/python-jenkins-demo.git"
                        }
                      }
                        stage("Run")
                            {
                            steps
                               {
                               sh "python3 app.py"
                               sh "python3 test_app.py"
                               }
                             }
}
 }
  