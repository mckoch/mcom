This project is to develop and document the  MicroContentObjectModel [XML scheme](XML.md) to express a basic model for snippets of micro content found on the internet. It is very basic and simple to use.

> The MicroContentObjectModel ([MCOM](MCOM.md)) describes single inline elements of content in their respective context. Every valid URL and/or DOM object is wrapped into an XML-desription which then can be handled in common programming languages or applications. Initially an [MCO](MCO.md) 'saves' informaton about the context in which it was found, along with a micro content copy in CDATA section.

> Developer may benefit from using MCOM objects in building websites by nesting related objects. End users  will benefit in better, more comfortable search results which are sensitive to context and semantics. Creatives may find it a way to build peer to peer networks made of content items from various sources.

> There is no special code or programming language except usage of XML schemes. MCOM is based on and 'compatible' with common object models like DOM and MVC. It may be used along with common scripting languages like PHP and Javascript.

A sample implementation of MCOM is BlooGee0.0f (project page  https://sourceforge.net/projects/bloogee/). Source code and CVS on http://bloogee.cvs.sourceforge.net/bloogee/BlooGee/ . A presentation is at http://docs.google.com/Present?revision=_latest&fs=true&docID=dhfz8pq8_29dq2skkgz.

This document describes the first version of the Micro Content Onject Model and an abstract class lib MicroContentObject (MCO). It is intended as a paper for thinking about, discussing and using an appropiate model to handle microcontent. This approach does not use keywords to find and glue related pieces of microcontent, it merely focusses - beyond computing relvancy from matching strings on web pages - on the fact that content preferably is linked to "real world" related content and applications, driven by criteria and ideas which are as individual as the context a collection of microcontent represents. Implementing MCOM should benefit the programmer as well as the user by accessing content and appropiate context in one convenient model.

> If you are in a hurry, just have a look on the  [class code](basic.md). You will find an MicroContentObject with some properties and three basic methods. The MCO-Model (see MicroContentObjectModel)closely corresponds to the DOM and MVC. Objects may be constructed in (at least) any web-orientated OOP-style programming language on client and server (this document uses "quasi" JavaScript/PHP).

