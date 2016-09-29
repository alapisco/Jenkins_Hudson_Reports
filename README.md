# Hudson Reports

This is a tool to generate reports from a Hudson server

The following reports are generated by the tool in separated csv files:

- General Report for all Hudson jobs 
- Jobs without configuration files
- Disabled Jobs
- Jobs bigger than a configurable size
- Jobs run more than a month ago

## Running the tool

- Create a property file for the reporter. There is a template in the dist folder.

- Copy the jar file in the dist folder to the server where you are running Hudson. 
  Make that the property file is in the same directory than the jar file.

- Execute the jar file:  java -jar Hudson_Reports.jar

Example:

![alt tag](https://raw.githubusercontent.com/alapisco/Hudson_Reports/images/u1.png)
