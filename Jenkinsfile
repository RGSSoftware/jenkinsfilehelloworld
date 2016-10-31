node {
    echo 'Hello World'
    sh 'whoami'
    sh('cd src && git rev-parse HEAD > GIT_COMMIT')
    git_commit=readFile('src/GIT_COMMIT')
    
    echo git_commit
}
