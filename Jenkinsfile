node {
    echo 'Hello World'
    sh 'whoami'
    //def pwd = pwd()
    //echo "${pwd()}@script"
    dir("${pwd()}@script"){
        echo pwd()
        sh('ls')
    }
    //sh('cd ../ && ls')
    
}
