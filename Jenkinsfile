properties([pipelineTriggers([cron('* * * * *')])])

node{
      stage("clone"){
        git "https://github.com/YoelEigner/MySoftware.git"
    }
    stage("run"){
      bat '''python -c "import button; button.click()"'''
      bat '''python -c "import screen; screen.welcome()"'''
    }
}
