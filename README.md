# LuciansHandBitMap-Font
Renders the characters from LuciansHandBitMap Font using a state machine.


# Installation from List Prolog Package Manager (LPPM)

* Optionally, you can install from LPPM by installing <a href="https://www.swi-prolog.org/build/">SWI-Prolog</a> for your machine, downloading the <a href="https://github.com/luciangreen/List-Prolog-Package-Manager">LPPM Repository</a>,
```
git clone https://github.com/luciangreen/List-Prolog-Package-Manager.git
cd List-Prolog-Package-Manager
```
loading LPPM with `['lppm'].` then installing the package by running `lppm_install("luciangreen","LuciansHandBitMap-Font").`.

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
