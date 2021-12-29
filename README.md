# PySpark Examples

[![pages-build-deployment](https://github.com/Ameykolhe/pySparkExamples/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/Ameykolhe/pySparkExamples/actions/workflows/pages/pages-build-deployment)

Home Page - [Link](http://ameyk.me/pySparkExamples/) <br>
Repository to store pyspark code

### Project Setup

1. Create .env file in project root directory
   ```
   MYSQL_DB=<MySQL Database name>
   MYSQL_USER=<MySQL Username>
   MYSQL_PASSWORD=<MySQL Password">
   MYSQL_ROOT_PASSWORD=<MySQL root Password>
   
   MONGO_ROOT_USER=<MongoDB Root Username>
   MONGO_ROOT_PASSWORD=<MongoDB Root Password>
   
   MONGOEXPRESS_LOGIN=<MongoExpress Username>
   MONGOEXPRESS_PASSWORD=<MongoExpress Password>
   ```
2. Docker data directories setup <br>
   1. Create the following Directory Structure
      ```
      data
        ├───elastic_search
        │   ├───1
        │   ├───2
        │   └───3
        ├───mongodb
        └───mysql
      ```
3. Download [MySQL Java connector](https://search.maven.org/artifact/mysql/mysql-connector-java/8.0.27/jar) and paste it in project root directory