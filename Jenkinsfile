pipeline {
    agent any
    stages {
        stage("Create important file!") {
            steps {
                sh """
                     touch important file1
                     touch important file2
                     touch important file3
                """     
            } //steps
            

            
        } //stage


        stage("Run helloworld") {
            steps {
                sh """
                    python helloworld.py 
                """

            } //steps


        
        } //stage
    } //stages   
} //pipeline