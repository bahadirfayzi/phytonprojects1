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
            

            
        } //stages
        
        stage("Run helloworld") {
            steps {
                sh """
                    python helloworld.py 
                """

            } //steps


        } //stage
        stage("Run game.py") {
            steps {
                sh """
                    python game.py
                """
            } //steps
        } //stage
    } //stages   
} //pipeline