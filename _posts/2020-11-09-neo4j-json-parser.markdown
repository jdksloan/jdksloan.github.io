---
title: "Neo4j JSON Parser"
last_modified_at: 2020-11-08T13:31:02-05:00
categories:
  - Blog
tags:
  - code
  - typescript
  - neo4j
---

Neo4j is a powerful graph database, that allows the storage and query of data in a graph format.

Since my transition to TypeScript and Graph theory, I've really enjoyed using this database, and since my previous article was about [Graph Structures]({% post_url 2020-11-08-graph-structures %}) I thought this would be a good follow up.

Neo4j is built in Java, I still don't really get this decision from them and when I queried why at the [2020 Graph tour](https://neo4j.com/graphtour/) the answer I got was becuase that's the stack their initial dev team was comfortable with. From my personal experience languages like C++ are superior for databases.

Seeing as Java is the language Neo4j speaks, in order to get the data into a clean readable JSON format, that TypeScript likes to work with, I had to create a parser.

I decided to share my hard work:

Have a look at my GitHub project page to see the code: [Graph data structures](https://github.com/jdksloan/ts-neo4j-parser).

Or install it using [npm i ts-neo4j-parser](https://www.npmjs.com/package/ts-neo4j-parser)

Yours Truly,

The Silent Coder.
