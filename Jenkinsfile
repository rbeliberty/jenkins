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
            if (action == 'synchronize') {
                echo 'action is synchronize'
            } else if (action == 'opened') {
                echo 'action is opened'
            } else if (action == 'labeled') {
                echo 'action is labeled'
            }else{
                echo 'action is not available'
                error('Aborting the build')
            }

        }
        stage('03 - Bye'){
            echo "End stage"
        }



    }
    finally{
        cleanWs()
    }



}