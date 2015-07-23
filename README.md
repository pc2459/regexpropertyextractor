# Regex Property Extractor

It's quick! It's dirty! It has bad css, a Google font, and inline scripts! But it works, and you can hack it till it does what you want. Which is to extract accessibility modifiers and types from a giant pre-existing list of C# properties given a list of property names. 

-P.S: yes, I'm aware this is all on the global scope and everything is awful. Refactor coming soon. But now to code what I was supposed to before getting distracted...-

Now with better javascript.

## What You Need

* A newline-delimited list of property names. 
* A chunk of C# to extract these from -- it can contain any amount of fluff, but the properties must be in the format of (accessibility modifier) (type) (property name), e.g. public FancyClass? ThingyName

The rest is pretty self-explanatory. 

