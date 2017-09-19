# ExagoNLP

Exago Business Intelligence is a software application that allows users to easily create their own reports and visualizations, and do analysis on the data that is being accessed.  A natural extension to this is NLP, where a user can ‘ask’ a question in either typed or voice input, and get an answer back based on the data in either displayed or voice (or potentially others such as SMS, email, etc.) output. 

We can understand what the person is requesting, but how to we write computer algorithms that can make these conclusions?  If we can’t understand what the request is, or there is ambiguity, can we build in a form of machine learning that asks the user for more specific information, then ‘learn’ from the response going forward?  How do we use the names of data objects (e.g. tables, views) and field names to help make educated conclusions about what the user is asking?
 
The purpose of the project is to interpret what the user is asking, form a query against the database, and return a result.  If there is uncertainty in the question, then ask a question back to the user and learn the answer going forward.  We plan to use the freely-available Northwind database for development purposes, as it is well structured and used commonly within our organization. Other databases may be used for testing; we’ll look to ensure that there are no references in the code to any specific database.
