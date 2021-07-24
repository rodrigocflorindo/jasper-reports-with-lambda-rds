# jasper-reports-with-lambda-rds
LambdaJReports com JasperReports
Este repositório hospeda o código para uma função Java Lambda que gera relatórios JasperReports em formato PDF, usando dados consultados de um banco de dados RDS MySQL. A função Lambda deve ser chamada por meio de uma API REST criada no API Gateway.

Junto com o código de função, este repositório contém um arquivo de modelo para JasperReports criado, "template.jrxml", e um script CloudFormation responsável por lançar os recursos necessários, "jasper-lambda-architecture.json". Ambos os arquivos estão localizados na raiz do repositório.
