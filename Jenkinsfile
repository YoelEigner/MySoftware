properties([pipelineTriggers([pollSCM('* * * * *')])])

node{
  stage("show"){
    bat "dir"
    bat '''python -c "import button; button.click()"'''
    bat '''python -c "import screen; screen.welcome()"'''
  }
}
