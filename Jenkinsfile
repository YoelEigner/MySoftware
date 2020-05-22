properties([pipelineTriggers([pollSCM('* * * * *')])])

node{
  stage("show"){
    bat '''python -c "import NewButton;click()"'''
    bat '''python -c "import NewScreen;welcome()"'''
  }
}
