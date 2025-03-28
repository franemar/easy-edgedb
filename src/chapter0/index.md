![leadImage_00](./src/chapter0/illustration_00.jpg)

# Welcome - Easy EdgeDB

Welcome to Easy EdgeDB! It's an illustrated textbook designed as a one-stop shop for learning EdgeDB.

```{eval-rst}
.. note::
  This book is also available in `Chinese </easy-edgedb/zh>`_.
```

We started writing this book shortly after the first alpha release of EdgeDB in Spring 2019. For the first time, we had a functional version of what we'd been thinking about for so long: an open-source database powered by PostgreSQL that combines the strictness of relational databases, the declarative schema of ORMs, and the painless deep querying of GraphQL—without sacrificing power, consistency, or performance.

While plenty of learning material can be found in the [documentation](https://www.edgedb.com/docs/), [interactive tutorial](https://edgedb.com/tutorial), and [blog posts](https://www.edgedb.com/blog), we wanted to put together a more immersive experience: a full textbook. The result is Easy EdgeDB: a book that's sufficiently comprehensive (and fun!) to shepherd an interested beginner through all basic and intermediate EdgeDB concepts.

Since then, EdgeDB has continued to grow — most recently with the launch of our [cloud service](https://www.edgedb.com/cloud) — and the Easy EdgeDB book [has grown along with it](https://github.com/edgedb/easy-edgedb/commits/master/).

Easy EdgeDB is a bit of a unique book. Here's how it differs from what you might expect from a typical e-book:

## A story to follow

The book is divided into 20 chapters in which we imagine that we are creating a database for a game. The setting for our imaginary game is the scenes and locations from the book Dracula by Bram Stoker, published in 1897. Our job is to think a little about how to represent items like characters, events, locations, and dates in the book in a database used by a role-playing game built separately. In other words, something like [Python](https://www.edgedb.com/docs/clients/python/index#edgedb-python-intro)/[JavaScript](https://www.edgedb.com/docs/clients/js/index#edgedb-js-intro)/[Go](https://github.com/edgedb/edgedb-go) on the frontend, and EdgeDB as the game's database.

Bram Stoker's Dracula was the perfect choice for this textbook for a few reasons:

* It's a fun read. We're excited to see you give EdgeDB a try and hope to make the introduction as painless and immersive as possible. We think that anyone who has spent an hour or so with EdgeDB will walk away excited about its possibilities, but for that to happen it's our job to make the experience a pleasant one. Bram Stoker's novel has really helped out here.
* It's a so-called _epistolary novel_: a novel written through the letters, diaries, and communications written by the main characters. That means that each entry has a date and an author, which makes it a great fit for a database.
* It's copyright free. Our book only scratches the surface of what a real database for a game based on this book would be like, but who knows? Maybe some readers will decide to take the concept a bit farther and make it into the real thing. And if that's the case, then an open source database software based on a book completely free of copyright is the best way to start.

## Plain English

We want to give as many people as possible the opportunity to sit down and give EdgeDB a try, and so we've opted for a style of writing that's simple and straightforward. We have three types of people in mind here:

* People unfamiliar with databases but ready to understand how they work if the concepts are explained in a straightforward way, 
* People who _are_ familiar with databases but don't want to wade through dense verbiage to learn a new database and query language, 
* People with English as a second (or third, fourth...) language who would much prefer reading a book in plain English for the same reason.

## Interactivity and experimentation

Because the book uses the events in the book for the background, we need a database to tie everything together. It will need to show the connections between the characters, locations, dates, and more. It starts with a simple schema (structure) and builds up from there, changing it as we go. The idea is to simulate the mental process for someone new to EdgeDB that has been given the task of putting this all together. That includes sometimes modifying the schema, creating new types, deleting ones that aren't used, and all the tinkering you'd see in real life.

Going through the book, we will learn how to use queries that are more and more complex. Each chapter contains the schema and inserted data that we've built up so far, and a REPL for you to experiment with. On top of that, each chapter has a number of questions for you to solve if you feel like a small challenge.

## Beauty

We looked far and wide, and didn't see any rule that a text on database software has to be dry and image free. To give a feel for the beauty of the original work (with a steampunk-ish vibe added for good measure) we teamed up with Damian Dideńko ([didiusz on Instagram](https://www.instagram.com/didiusz/)), an illustrator from Katowice, Poland, to put together some beautiful sketches that combine the atmosphere of the book Dracula with the most important schema and query concepts per chapter.

Putting all the above items together results in a book that blends the old and the new in a form that we hope will keep you turning the page as you familiarize yourself with EdgeDB and discover what it has to offer you.

[So let's get started - on to Chapter 1!](../chapter1/index.md)
