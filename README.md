![MongoDB](./images/header.png "MongoDB")
# Getting MEAN
## An Introduction to Modern, API-centered Application Development with Node.js and MongoDB
## Background
This repository was created as a resource for a blog article being written for MongoDB as well as for a talk to be delivered at MongoDB World 2018.  It was designed to be consumed in stages by branch and will culminate in the creation of a functional application and API that creates, reads, updates and deletes data from and within a MongoDB database.

The title of the talk is "Zero to Hero in 80 minutes with the Node.js and MongoDB".  That's a tall order.  Let's first address the first and most obvious question: What is a hero?

## he·ro ##
ˈhirō/Submit

_noun_

1. a person who is admired or idealized for courage, outstanding achievements, or noble qualities. "a war hero"
synonyms:	brave person, brave man/woman, man/woman of courage, man/woman of the hour, lionheart, warrior, knight;

2. NORTH AMERICAN another term for submarine sandwich.

So I'm either going to impart to you a series of teachings, tools, weapons and resources that will enable you to become a brave, courageous person that can be admired for noble qualities, or I'm going to teach you to become sandwich-like... or both.

The format of the workshop is simple.  We'll leverage a series of quests.

## Weapons, Tools and Resources
* [MongoDB Download Center](https://www.mongodb.com/download-center#community)
* [Node.js](http://nodejs.org)

## Concepts
* [Application Programming Interfaces (APIs)](https://en.wikipedia.org/wiki/Application_programming_interface)

### Document Model
MongoDB is a post-tabular database platform that leverages a `document model` to store data.  This means simply that it leverages documents rather than tables.  Documents consist of JavaScript Object Notation (JSON) structures.  These structures are comprised of key/value pairs inwhich the keys are always strings and the values can be one of many types including:
* Strings
* Numbers
* Arrays
* Nested Objects - Sometimes referred to as subdocuments.

Here's an example of a document:

```
{
    '_id' : 1,
    'name' : { 'first' : 'John', 'last' : 'Backus' },
    'contribs' : [ 'Fortran', 'ALGOL', 'Backus-Naur Form', 'FP' ],
    'awards' : [
        {
            'award' : 'W.W. McDowell Award',
            'year' : 1967,
            'by' : 'IEEE Computer Society'
        }, {
            'award' : 'Draper Prize',
            'year' : 1993,
            'by' : 'National Academy of Engineering'
        }
    ]
}
```
For additional information, see [MongoDB JSON/BSON Documents
](https://www.mongodb.com/json-and-bson)
### Importing Data

## Helpful Hints
We'll continues working on this together. If you have a question or problem, let one of the mentors know.

## Next
What's next?  Ready to start your journey of development?  Continue on from here to the workshop.  There are X stages or branches of development in the workshop.  If you successfully complete each branch or stage, you'll end up with a fully functional API-centered application written in Node.js.

Next Quest: [Quest Zero](./workshop/quest0.md) - Introduction to quests and some basics.