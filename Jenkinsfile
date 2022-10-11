pipeline{
    agent any 
    stages{
        stage("Install requirements"){
            steps{
               sh "pip3 install -r requirements.txt"
            }
        }
        stage("Running flask app"){
            steps{
                sh "python3 app.py"
            }
        }
    }
}
