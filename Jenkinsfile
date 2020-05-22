properties([pipelineTriggers([cron('*/30 * * * *'), githubPush()])])

node{
      stage("clone"){
        git "https://github.com/YoelEigner/MySoftware.git"
    }
    stage("run"){
      bat "dir"
      bat '''python -c "import button; button.click()"'''
      bat '''python -c "import screen; screen.welcome()"'''
    }
}
