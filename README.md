## Jasper Reports with Lambda, RDS and API Gateway

This repository hosts the code for a Java Lambda Function that generates JasperReports reports in PDF format, using data queried from an RDS MySQL database.
The Lambda function is meant to be invoked through a REST API created in API Gateway.

Along with the function code, this repository contains a template file for the JasperReports, "template.jrxml", and a CloudFormation script
responsible for launching the required resources, "jasper-lambda-architecture.json". Both files are located in the root of the repository.

##

