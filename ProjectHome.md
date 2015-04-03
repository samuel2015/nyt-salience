[Link to download the data](https://drive.google.com/open?id=0B6s2fODjrU7Kc2JtTTNVWlY1c1U&authuser=1)

## New York Times corpus add-on annotations: MIDs and Entity Salience. ##

The data included in this release accompanies the paper, entitled
"A New Entity Salience Task with Millions of Training Examples" by
Jesse Dunietz and Dan Gillick (EACL 2014).

The training data includes 100,834 documents from 2003-2006, with
19,261,118 annotated entities. The evaluation data includes 9,706
documents from 2007, with 187,080 annotated entities.

An empty line separates each document annotation. The first line of
a document's annotation contains the NYT document id followed by the
title. Each subsequent line refers to an entity, with the following
tab-separated fields:

entity index
automatically inferred salience {0,1}
mention count (from our coreference system)
first mention's text
byte offset start position for the first mention
byte offset end position for the first mention
MID (from our entity resolution system)