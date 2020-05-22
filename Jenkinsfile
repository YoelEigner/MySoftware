properties([pipelineTriggers([pollSCM('* * * * *')])])

node{
  stage("show"){
    bat '''python -c "import button; button.click()"'''
    bat '''python -c "import screen; screen.welcome()"'''
  }
}
