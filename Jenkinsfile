pipeline {
   agent any

   stages {
   
       stage('Print')
       {    steps
            {
              echo 'Hello world'
            }
       }
       
     /*  stage('Restore Nuget')
       {    steps
            {
           bat 'c:/tools/nuget.exe restore SeleniumNUnitParam.sln'
            }
       }
       
        stage('Build')
       {
           steps{
              bat '"\"${tool 'MSBuild'}\" SeleniumNUnitParam.sln  /p:Configuration=Release;/nodeReuse:false'
          
          // Platform=${env.PLATFORM} /maxcpucount:%NUMBER_OF_PROCESSORS% 
              //C:/Program Files (x86)/Microsoft Visual Studio/2017/BuildTools/MSBuild/15.0/Bin/MSBuild.exe
           
           }
       }*/
       
   }
     
}
