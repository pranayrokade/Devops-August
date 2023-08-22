pipeline                         //Jenkinsfile always starts with keyword pipeline
{ 
    agent any                    //agent any means : any available executor
    stages                       //it contains all the stages
    {
        stage ('GIT scm checkout')  //name of the stage
        {steps                   //it tells jenkins what to do
        {sh 'echo downloading_code_from_github'}}  //sh: execute the shell script/command

        stage ('Execute Unit Test case')  //name of the stage
        {steps                   //it tells jenkins what to do
        {sh 'echo executing_test_cases'}}

        stage ('Code Build')  //name of the stage
        {steps                   //it tells jenkins what to do
        {sh 'echo building_the_Code'}}
    }
} 