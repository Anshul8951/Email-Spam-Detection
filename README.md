# Spam-email-Detection
Implementation of a machine learning model to predict whether a message is spam or not. Furthermore, you will create a system that upon receipt of an email message will automatically flag it as spam or not, based on the prediction obtained from the machine learning model

# AWS Services Used
  1. **Sagemaker** to build and train and spam filter ML model
  2. **AWS s3 bucket** to store emails which can be further analysed for spam detection
  3. **SES** to set up an email address that upon receipt of an email will save it in s3
  4. **CloudFormation** for representing the infrastructure resources and permissions

