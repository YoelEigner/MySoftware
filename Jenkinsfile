properties([pipelineTriggers([pollSCM('* * * * *')])])

node{
  stage("show"){
    bat '''python -c "click()"'''
    bat '''python -c "welcome()"'''
  }
}
