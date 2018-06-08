# RAFT (Randy's ANSI Flowchart Text)
An inline language for writing standardized [ANSI](https://www.ansi.org/) flow charts with simple text.

## Objectives

RAFT's goal is to make an easy way to create flows within text based documention without the use of images or visual editors. 

## Spec

* It needs to work alongside Markdown and not get compiled to HTML when markdown is converted
* It needs to use non-special characters everyone has access to
* It needs to follow a standard that would allow it to be rendered into a visual flow chart
* It needs to be as simple as possible
* It needs to be quickly read and understood by a human

# Symbols

Text representation of ANSI/ISO Standard Symbols taken from https://en.wikipedia.org/wiki/Flowchart

## Common Symbols

-> Flowline of Control ->

( Terminal )

[ Activity or Process or Operation ]

< Decision >

/ Input or Output /

-[ Annotation ]-

[[ Predined Process ]]

( C ) `An on-page connector that uses a single letter that is tied to a definition written in a legend`

{ Off-page Connector }

## Other Symbols

(_( Datafile or Database )_)

~ Document ~

== Parallel Mode ==

^/ Manual Operation ^/

[ Physical Movement ]=>
