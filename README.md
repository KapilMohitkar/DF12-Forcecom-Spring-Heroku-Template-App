
# Spring MVC Template for Salesforce

I wrote up notes from a Dreamforce 12 session about setting up a Java Spring app that runs on Heroku and talks to a Salesforce org. I wanted to share the code that was generated from this session, so you can reference it from my notes.
http://alexdberg.blogspot.com/2012/11/sunday-project-forcecom-spring-app-on.html



-------------------------

This is a template for a Spring MVC web application to work with data from Salesforce.
The sample code is a dynamic CRUD application that allows users to create, read, edit, and delete any Salesforce object.
It is backed by the [Rich SObjects](https://github.com/ryanbrainard/richsobjects) library for interactions with Salesforce.

## Getting Started

1. [__Clone Now__](https://api.heroku.com/myapps/template-java-spring-sfdc/clone)
2. Setup your salesforce.com OAuth Remote Access. You will then have a OAuth client key and secret
3. Update the Environment variables to include the OAuth client key and secret
4. Navigate to the "contacts" page and you should now be authenticated against salesforce and view/create/update/delete contacts
