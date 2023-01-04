# cloud-formation template with lambda and apigateway
# cloud-formation template with lambda and apigateway
STEPS TO CREATE JENKINS FILE TO DEPLOY CLOUD FORMATION TEMPLATE WHEN GIT COMMIT IS MADE:
 1) Create Jenkins server and enter into the jenkins.
 2) Add the github credentials using the following steps Dashboard > Manage Jenkins > Credentials > Global credentials (unrestricted)> Adde Credentials >Select Kind username&password .
 3) Install AWS Credentials plugin to add AWS credentials
 4) Add the AWS credentials using the following steps Dashboard > Manage Jenkins > Credentials > Global credentials (unrestricted)> Adde Credentials >Select Kind AWS credentials.
 5) Select pipeline job and give the github repositry url 
 6) Select Github SCM polling option and enter the github repositry url 
 7) Add Webhook if you need to change for every commit.
 8) Check the jenkins file for the pipeline script and cloud formation template for the createion of lambdaapigateway stack. 
  
