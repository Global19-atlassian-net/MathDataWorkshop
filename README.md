# Math Data Workshop

[Nicolas' notes on logistics](https://hackmd.io/4b8zBeKLS6i9w84G0ChanA?view)

[Arrivals and departures](https://hackmd.io/HR0KV8IJT2qlAOqRBhqW6A)

[Food planning](https://hackmd.io/XC6rJLLiThWVMjXM7wF-XQ)

Sheets and towels should be there. Bring toiletries!

#### TODO for Saturday morning

* Move food to La Tour
* Move one of the two white cutting boards from Le Roi Soleil to Le Petit Prince

## Bring to the workshop / Preparations

- Transfer data to server pre-workshop (the internet access will not support transfering large amounts of data)
- Fresh food for Saturday and Sunday (Samuel and Katja)
- A few power strips
- Scrap paper

## Things to do or figure out

### Datasets

#### List of target datasets
- Abstract polytopes and maniplexes (Gabe, Katja)
- Symmetric graphs (Katja, Gabe)
- Lattices (Jukka)
- Small Groups Library export (Michael T., Katja)

#### Things to do with each

1. Prioritize (make list in order of importance) properties of datasets for the other dataset tasks.
2. Write schema theories
3. Formalize relevant math
4. Import into
5. Provenance

Initial assignments:
- 1: Gabe, Jukka, Katja
- 2 and 3: Gabe, Jukka, Katja, Michael T. with Dennis
- 4: Gabe, Jukka, Katja, Michael T. with Tom

#### Other

- Connect the small groups with [Group Names](https://people.maths.bris.ac.uk/~matyd/GroupNames/index.html) and the [Group Explorer](https://nathancarter.github.io/group-explorer/GroupExplorer.html).
- How to deal with the above in general way, (so that the below can also be handled) so that we can add such things without too much work - Florian?
- How to deal with [p-adic](https://gitlab.com/mathzeta2/zetalib/blob/master/zetalib/p-adic-examples.json)
- Come up with a good name for the fourth kind of mathematical data (previously known as concrete/relational/...)
- Think about recording provenance
- Think about a journal of math datasets

### Datatypes and Codecs

Our MDDL (math data description language) defines two kinds of objects:
* datatypes specify types using their mathematical properties, such as
  ** basic types: integers, rationals, booleans, etc.
  ** collection types: vectors, matrices, finite sets, multisets, etc.
  ** higher mathematical types: polynomials, rings, etc.
 * codecs specify translations (and back) from datatypes to primitive types supported by databases, such as
  ** integers as strings, integers as lists of base 2^64 digits, etc.
  ** sparse vector codec (i.e., vectors as sparse lists), taking a codec for the entries as an argument

The datatypes are formally specified and the codecs are named and documented in the file https://gl.mathhub.info/ODK/discretezoo/blob/master/source/MDDL.mmt

This file serves as the reference for our implementations.
It will probably be extended substantially during the course of the workshop.

### Interface

- Choosing collections (defaults?), choosing columns displayed by default
- Support the filter box with autocomplete-type search (in case there are many)
- Usability: intro tour of the interface (see [intro.js](https://introjs.com/)), pop-up definitions
- Out there: new graphic image and/or colour scheme to integrate with MathHub?

#### Computer algebra system integration

- How to do it? - MitM
- Sage explorer connection?

## Links

- You can help with the [survey of math datasets](https://mathdb.mathhub.info/)!

## Participants

Legend:
* ***(v)***: (known/prefers) vegetarian/vegan
* ***[person]***: room sharing or similar

Participants:
* Odile Bénassy? [probably Katja]
* Katja Berčič (v, no mushrooms) [probably Odile]
* E. Madison Bray
* Gabe Cunningham
* Dennis Müller
* Andrea Kohlhase [Michael]
* Michael Kohlhase [Andrea]
* Jukka Kohonen
* Samuel Lelièvre (v)
* Florian Rabe
* Julian Rüth [tent]
* Nicolas Thiéry [tent]
* Michael Torpey
* Tom Wiesing
