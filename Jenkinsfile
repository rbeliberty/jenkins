node{
    cleanWs()
    try{
        stage('00 - Check env var'){

            if (x_github_event == 'pull_request') {
                echo 'x_github_event is pull_request'
            } else {
                echo 'x_github_event it not pull_request'
                error('Aborting the build')
            }
        }

        stage('01 - Stage'){
            echo "Hello World !"
        }
        stage('02 - Stage'){
            echo "pull_request action is : " + action
        }
        stage('03 - Bye'){
            echo "End stage"
        }



    }
    finally{
        cleanWs()
    }



}