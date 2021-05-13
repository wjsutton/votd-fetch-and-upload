<h1 style="font-weight:normal"> 
  Viz of the Day: AWS Workflow 
</h1>

[![Status](https://img.shields.io/badge/status-active-success.svg)]() [![GitHub Issues](https://img.shields.io/github/issues/wjsutton/votd-fetch-and-upload.svg)](https://github.com/wjsutton/votd-fetch-and-upload/issues) [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/wjsutton/votd-fetch-and-upload.svg)](https://github.com/wjsutton/votd-fetch-and-upload/pulls) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

:construction: Repo under construction :construction:

[Twitter][Twitter] :speech_balloon:&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[LinkedIn][LinkedIn] :necktie:&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[GitHub :octocat:][GitHub]&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Website][Website] :link:

<!--/div-->

<!--
Quick Link 
-->

[Twitter]:https://twitter.com/WJSutton12
[LinkedIn]:https://www.linkedin.com/in/will-sutton-14711627/
[GitHub]:https://github.com/wjsutton
[Website]:https://wjsutton.github.io/

### :a: About
The AWS workflow for the Viz of the Day data set daily refresh, using AWS Lambda functions, AWS S3 and Google Sheets.

#### Overview Diagram
<img src="https://github.com/wjsutton/votd-fetch-and-upload/blob/main/Diagram.png?raw=true">


## TO DO:

### Setup

- Google Sheet
- Google Sheets Writer API 
- AWS Secrets Manager
- AWS IAM Roles

### AWS Lambda Layers

- Pandas, OAuth, Gspread

### Lambda Function - Fetch data and save to S3

- IAM Role
- Call Tableau Public API
- Save to S3

### Lambda Function - Read S3 data and upload to Google Sheets

- IAM Role
- Read S3 bucket data
- Call Secrets Manager
- Write to Google Sheets
