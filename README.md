# nasper

## language justification

A lot of langauges have nice semantic properties but are not hardware aware because they build their primatives in lala land (functional languages).
Other languages are hardware aware but do not have nice semantic properties becuase they make everything about programming against hardware, which fails to recognize the howard-curry isomorphism (we have a language for the transformation of data, its called math!).

This lanugage seeks to allow for having both nice semantic properties and being hardware aware by providing primatives that are hardware aware (set, dict, list (arraylist, not linked list), monomorphized streams and functions), which is made possible by linear typing, and providing the ability to create new such primatives via the unsafe module... while also retating the composition of these primatives via the semantics of functional programming.

I have also put in the work of making everything as ergonomic as possible... this is not a research langauge, its is an application of research that has not made its way to industry... into industry.

## some lanugage features

linear types, monomorphized first class streams, fully functional, as fast as C, as ergonomic as python (I kinda want to make it slower than C tho... int should be arbirarily sized by default and kinda of want to do strs as non-linear value types)

oh also monomorphized existential typing...

look at the lisp module for some basic use cases

if you clone this thing... lua is pretty good for syntax highliting

oh and also besides strs (maybe) the language is not garbage collected
