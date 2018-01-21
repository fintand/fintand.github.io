---
layout: post
title:  "Cedar Driving School"
tech: "Angular 4, AWS Lambda, AWS DynamoDB"
date:   2017-05-26 19:10:15 +0000
---

Cedar Driving School is a website for an excellent driving instructor, you can find their website [here](https://cedardrivingschool.ie/).

At the time of being asked to create this website. I was very curious about the latest Angular. I decided to try it out using the Angular CLI.
I got to learn how Typescript works and the major differences with AngularJS.

For hosting I used Firebase hosting as they host the code on their global CDN, provide a free SSL cert and have a great CLI making deployments
simple and fast.

For the contact page I decided to use a simple API. This was achieved using the [Serverless framework](https://serverless.com/) which created
an AWS Endpoint and used an AWS Lambda function. Each user who used the contact page got stored in AWS DynamoDB.
