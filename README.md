# Experiments with assembly language
Some experiments I did as a graduate student in computer science to dive into assembly language.  

## The Mic1
The micro architecture simulator, Mic1, is offered in the classic book by Tanenbaum (2005), _Structured Computer Organization_, section 4.3.1 and an interpreter for the Mic1 microarchitechture specified in section 4.1.

It is a set of tools to explore microarchitecture. It consist of an assembler for the Micro Assembly Language (MAL) and an interpreter for the Mic1 microarchitechture.

The assembler, mic1-asm, translates a MAL program into a 512 word image for the Mic1 control store. The interpreter, mic1, loads this control store image and optionally an IJVM bytecode file and then simulates the Mic1 machine.

## More info
http://cis.stvincent.edu/carlsond/cs330/mic1/mic1.html

https://users-cs.au.dk/bouvin/dComArk/2015/noter/Note_3/index.html
