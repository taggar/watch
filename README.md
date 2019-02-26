# A Showcase for Separating Content from Form

In a Hurry? Scroll to the end!

## Some History

### The Problem 

*Electronic manuscripts contained control codes or macros for formatting/layout.* In other words: content and layout were all mixed up in the same "machine code", **specific to the process that was being performed and to the system that was performing it. These codes and macros tended to be proprietary, leading to **issues of exchange, and repeated typesetting costs** (e.g. when printers were using different printing presses, or when a press was replaced by a new one from a different manufacturer).

### The Spark: GCA GenCode&reg;

September 1967: a Presentation by William Tunnicliffe from the GCA (Graphic Communications Association) at the Canadian Government Printing Office  on **"The separation of information content of documents from their format"** leads to 
the start of the *generic coding movement* (for example, instead of "format-17" use "heading") and a "Generic Coding" project inside the GCA Composition Committee.

### IBM's GML

In 1969, three guys at IBM conduct a project for integrated law office information systems: Goldfarb, Mosher, and Lowrie. They come up with the *Generalized Markup Language* (**GML**), as a means of allowing text editing, formatting, and information retrieval systems to share documents. GML is based on the generic coding ideas, but rather than a tagging scheme it introduces the concept of a formally-defined document type with an explicit nested element structure. 

GML was implemented in mainframe industrial-strength publishing systems. (IBM was the second largest publisher in the world!)

### ANSI

In 1978, the ANSI committee on Information Processing starts a project on *Computer Languages for the Processing of Text*. They ask *Goldfarb* to lead the project for a *text description language based on GML*. A first working drft is published in 1980. Draft 6 is issued in 1983 and adopted by the US Internal Revenue Service (IRS) and Department of Defense (DoD).

### ISO

In 1984, ANSI and ISO team up in ISO/IEC JTC1/SC18/WG8. They issue a draft standard for **SGML** - Standard Generalized Mark-up Language - in October 1985. 

In 1986, the first approved version of SGML is published - using a system developed internally at **CERN** -as ISO 8879:1986, .

### HTML

In 1980, Tim Berners-Lee prposed a system for researchers to use and share documents. In 1989 he proposes an internet-based hypertext system with a simple HyperText Mark-up Language, strongly inspired on SGMLguid (a CERN Application of SGML). Together with Robert Cailliau he develops a first version (18 elements!)

### XML and CSS

1996, the proliferating practice of creating web pages that - again - mix content and formatting instructions and use HTML as a formatting language sparks a movement for 

* more semantics (an SGML for the web, later to be XML)
* a separate way of coding style and layout (CSS, Cascading Style Sheets)

## Illustrating the Idea of Separating Content from Form

http://www.csszengarden.com/

* Identical html
* different images and CSS
* resulting in [radically different visuals](http://www.mezzoblue.com/zengarden/alldesigns/)!
