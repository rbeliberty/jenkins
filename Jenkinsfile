node{
    cleanWs()
    try{
        stage('01 - Stage'){
            echo "Hello World !"
        }
        stage('02 - Stage'){
            echo "git repository name is : " + repository_name
        }
        stage('03 - Stage'){
            echo "author of commit is : " + commit_author
        }
        stage('04 - Stage'){
            echo "pull_request action is : " action
        }
        stage('05 - Bye'){
            echo "End stage"
        }





    }
    finally{
        cleanWs()
    }


}