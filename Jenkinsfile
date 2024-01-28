pipeline{
  agent any
  parameters{
    booleanParameters(name:"value1",description:"new value",defaultValue:true)
  }
  stages{
    stage("stage1"){
      steps{
          sh "echo '${params.value1}'"
      }
    }
    stage("stage2"){
      steps{
      sh "echo 'hello'"
      }
    }
    stage("stage3"){
      steps{
      sh "echo 'hello'"
      }
    }
    stage("stage4"){
      steps{
      sh "echo 'hello'"
      }
    }
  }
}
