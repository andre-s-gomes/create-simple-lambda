# create-simple-lambda
Creating a Simple AWS Lambda Function
Description
This Learning Activity provides hands-on experience with creating and customizing Python3-based Lambda functions from within the console.

The primary focus will be on the following features within AWS Lambda:

Lambda Console
Function Code
Execution Roles
Test Events
Execution Results
AWS Lambda allows you to create functions and you only have to worry about managing your code. AWS handles the underlying infrastructure for you.

This HelloWorld function will allow you to see just how easy it is to get started.

Objectives
Successfully complete this lab by achieving the following learning objectives:

Create a Lambda Function within the AWS Lambda Console

Navigate to the Lambda portion of the AWS Console.
Select Create your Lambda Function from scratch.
Select Python3.6 as your runtime.
Copy the code from the example code provided.********************************************
Deploy your function after adding the sample code.
Create a Test Event and Manually Invoke the Function Using the Test Event

Select the drop-down next to Test at the top of the Lambda console.
From the drop-down, select Configure test events.
Select the Hello World event template.
Erase the code in there and copy and paste the provided JSON code, then select Create.
Click on the Test button and verify your function succeeds.
Verify that CloudWatch has Captured Function Logs

Navigate to the CloudWatch portion of the AWS Console.
Select Logs from the selection on the left.
Select the log group with your function name in it.
Select the log stream within the log group.
Verify the output is present and correct.
