# LuciansHandBitMap-Font
Renders the characters from LuciansHandBitMap Font using a state machine.

# Installing

* Please download and install <a href="https://www.swi-prolog.org/build/">SWI-Prolog</a> for your machine.

* Download this repository to your machine.

* Load the Split on Phrases program by typing:
`['characterbr.pl'].`

* The algorithm is called in the form:
`ctobr0.`

* This gives the output:
```
A

[]	[]	[1,2]	[]	[]	
[]	[]	[1,2]	[]	[]	
[]	[1]	[]	[2]	[]	
[]	[1]	[]	[2]	[]	
[]	[1,3]	[3]	[2,3]	[]	
[1]	[]	[]	[]	[2]	
[1]	[]	[]	[]	[2]	
[]	[]	[]	[]	[]	
[]	[]	[]	[]	[]	

  *  
  *  
 * * 
 * * 
 *** 
*   *
*   *
```
* etc.

* Alternatively, the algorithm may be called with:
`ctobr('A').`
* Where `'A'` may be replaced with another character name.

# Authors

Lucian Green - Initial programmer - <a href="https://www.lucianacademy.com/">Lucian Academy</a>

# License

I licensed this project under the BSD3 License - see the LICENSE.md file for details
