node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.

   // Mark the code build 'stage'....
   stage 'Build'
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/c146a7f4-d5ec-4856-954f-2e8e2c326acd@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/4805fa86ff6746f0a268873c0633e8e2/11a97ad3-e780-471d-abd5-0abddae8e624', color: '800000'
   // Run the maven build
}



