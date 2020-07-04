pipeline  
{
  agent any
  stages
  {
    stage ('git clone')
    { steps
     { sh 'downloading clone'}
    } 
    stage ( 'code build')
    { steps
     { sh 'echo code ic building' }
    }
    stage ('get approval')
    {steps
     { inputs "Please approve the deployementstage?"}
    }
    stage ('deployment')
    {steps
     {sh 'echo code is deploying'}
    }
    
  }  
}
