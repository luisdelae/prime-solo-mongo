# prime-solo-mongo

Description
In this challenge, we’re going to practice basic Mongo syntax. This should help better solidify some concepts that were covered during lecture.

Assumptions
You are using the mongo shell or Robomongo
You installed mongo via homebrew
mongod is currently running on your computer
Setup
Follow the instructions below before continuing with this challenge.

Create your database
We are creating a database to hold a collection with at least 3 documents.

Open mongo shell
Type use iota to create your database (or use an existing database)
GitHub repo
Create a GitHub repo named “prime-solo-mongo”.
Create a file called “mongo.txt”. You will store your responses to the exercise questions here.
Exercise
For each of the following questions

Write a comment that specifies which question you are answering. Use JavaScript comment syntax.
Write the Mongo query that answers the question, below that comment.
Example question and answer
// 0. Create a collection named joe
db.createCollection('joe')
Tasks
Create a collection named orders.
Insert at least 3 documents that represent an order. IMPORTANT: See section below for fields.
Find a single order document, any order document.
Find all orders and make them look pretty.
Find all orders with an orderDate that is prior to 1/1/2016.
Find all orders with an orderDate that is after 1/1/2016.
Find orders with lineItems that have a quantity that is less than 50, but greater than 5.
order fields
orderDate -- see https://docs.mongodb.org/manual/reference/method/Date/
orderTotal
lineItems -- a sub-document that can accomodate many line items with fields: unitPrice, quantity, productName
