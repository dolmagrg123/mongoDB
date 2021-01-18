# mongoDB

MongoDB is a NoSQL database that uses documents to store data in an organized way.

## NoSQL document database:

MongoDB does not utilize tables, rows and columns to organize data and it uses a structured way to store and access data.

#### Document:

A way to organize and store data as a set of filed-value pairs.

#### Collection:

An organized store of documents in MongoDB, usually with common fileds between documents.


## Atlas:

Fully built database with mongoDB at its core for data storage and retrieval.
Atlas users can deploy clusters:

#### Clusters: 
A group of servers that stores your data

#### Replica Set:
A few connected MongoDB instances that store the same data. 

When you deploy your code or make changes redundant copies of you data are stored. If any of the machines in the replica sets fails, the data still remains intact and available for use by the other working replica sets.

#### Instance:
A single machine locally or in the cloud running a certain software. In pur case, it is mongoDb database running in the cloud.

## Uses of Atlas

* Manage cluster creation
* Run and maintain database deployment
* Use cloud service provider of your choice
* Experiment with new tools and features


## JSON


JavaScript Standard Object Notation

JSON fromat: 

* Start and end with curly braces {}
* Separate each key and value with a colon :
* Separate each key:value pair with a comma ,
* "keys" must be surrounded by quotation marks ""
        Keys are also known as fields in mongoDB.

#### Pros of JSON

Friendly, Readable and Familiar

#### Cons of JSON

Text-based, Space consuming and Limited


## BSON

MongoDB stores data in BSON, internally and over the network. BSON bridges the gap between binary representation and JSON format

#### Optimized for:
* Speed
* Space
* Flexibility
#### High performance
#### General purpose focus

### Data

MongoDB stores data in BSON and then you can view it in JSON. BSON is faster to parse and lighter to store than JSON.













