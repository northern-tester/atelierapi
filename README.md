## Synopsis

At the top of the file there should be a short introduction and/ or overview that explains **what** the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

A list of available endpoints can be found here:

Organisers

GET /organisers
GET /organisers/{id}
POST /organisers
PUT /organisers/{id}
DELETE /organisers/{id}

Ateliers

GET /ateliers
GET /ateliers/{atelierid}
POST /ateliers
PUT /ateliers/{atelierid}
DELETE /ateliers/{atelierid}

Speakers

GET /speakers
GET /speakers/{atelierid}
GET  /speakers/{atelierid}/{speakerid}
POST /speakers/{atelierid}/{speakerid}
PUT  /speakers/{atelierid}/{speakerid}
DELETE /speakers/{atelierid}/{speakerid}

Content

GET /content
GET /content/{contentid}
POST /content/{contentid}
PUT /content/{contentid}
DELETE /content/{contentid}

## Tests

Running npm test will run all tests

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)