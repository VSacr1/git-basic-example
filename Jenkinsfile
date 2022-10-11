pipeline{
    agent any 
    stages{
        stage("Install requirements"){
            steps{
                pip3 install -r requirements.txt
            }
        }
        stage("Running flask app"){
            steps{
                python3 app.py
            }
        }
    }
}
