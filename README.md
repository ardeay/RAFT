![RAFT](RAFT.png "RAFT")

# RAFT (Randy's ANSI Flowchart Text)
A language for writing standardized [ANSI](https://www.ansi.org/) flow charts with simple text.

## Objectives

RAFT's goal is to make an easy way to create flows within text based documentation without the use of images or visual editors.

## Spec

* It needs to work alongside Markdown and not get compiled to HTML when markdown is converted
* It needs to use non-special characters everyone has access to
* It needs to follow a standard that would allow it to be rendered into a visual flow chart
* It needs to be as simple as possible
* It needs to be quickly read and understood by a human

## Examples
```
( Server )  ->  Flowline Comment  ->  ] Handles Request [  ->  // prepares data for database insertion //  ->  ((( Database X )))
```
# Symbols

Text representation of ANSI/ISO Standard Symbols taken from https://en.wikipedia.org/wiki/Flowchart

## Common Symbols

 ->  Flowline  -> `flowlines have two white spaces before and after the -> mark`

( Terminal )

] Activity or Process or Operation [

< Decision >

// Input or Output //

-[ Annotation ]-

]] Predefined Process [[

( C ) `An on-page connector that uses a single letter that is tied to a definition written in a legend`

{ Off-page Connector }

## Other Symbols

((( Datafile or Database )))

~ Document ~

== Parallel Mode ==

^/ Manual Operation ^/

[ Physical Movement ]=>
