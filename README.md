# aws-lambda-ts-boilerplate

Boilerplate to kickstart creating a AWS Lambda using typescript.

This project is Continuous Delivery ready via AWS CodePipeline. Follow [this]('https://docs.aws.amazon.com/lambda/latest/dg/build-pipeline.html') tutorial from AWS to create your pipeline.

## **observations**

1. Make sure to change 'myFunction' to your function name in template.yml file. While you are there, change the 'Description' aswell.

2. Also change the name and description in the package.json to your function.

3. Also change the 'BUCKET' name on the buildspec.yml file to the s3 bucket that you want to store your artifacts.
