# Agile Scrum Sprint Velocity DataSet

Scrum is the mostly used Agile methodology today. This dataset is prepared for my final year project in 2020. Data of following four Opensource projects are included here.

| Project  | Board ID | Base URL |
| ------------- | ------------- |-------------|
| Spring XD |  43|https://jira.spring.io|
| Meso |  62|https://issues.apache.org/jira|
| Aurora |  37|https://issues.apache.org/jira|
| UserGrid |  23|https://issues.apache.org/jira|

Each folder contains 3 comma seperated csv files
1. X Issues n.csv
2. X Issues summery n.csv
3. X Sprints n.csv

X is the project name. n is the number of rows in dataset

#### API Used
<a href="https://docs.atlassian.com/software/jira/docs/api/REST/7.6.1/">JIRA REST API</a> and <a href="https://community.atlassian.com/t5/Jira-questions/How-to-access-Sprint-details-using-Api/qaq-p/512783">Greenhopper</a> API

#### Highlights
* New lines, tabs and commas were removed from strings
* Number of developers of a team determined by counting number of assignees within sprint
* Data should pre-preocess before use
* Some inappropriate data were removed

Thank You.

Randula Koralage
