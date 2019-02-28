# About

This project will eventually be an open-source implementation of my SOJM server.

SOJM is a tool I wrote for workers on Mechanical Turk help *"gamify"* the working experience by allowing users to compare against and/or compete with one another.

# Purpose / History

My initial intent in writing SOJM was to practice using Lambda, DynamoDB, CloudWatch, and API Gateway that I'd learned to use in an AWS course I'd completed.

Later, I'd bought a couple of Raspberry Pis and wanted to see whether I could migrate the server from AWS to a Pi with minimal-to-no code modification. I found DynamoDB local, had to compile some of the relevant tools for Raspbian, and had to handle some configuration issues, but I eventually migrated the tools by adding a thin Express wrapper around the Lambda functions.

By developing a new open-source implementation of the server, I imagine that Turkers will be able to run their own leagues. I will be able to implement a *"cleaner"* version of the fairly-dirty code *(a thin Express wrapper hack around what was originally a "first Lambda functions" project)*.
