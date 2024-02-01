# LuciansHandBitMap-Font
Renders the characters from LuciansHandBitMap Font using a state machine.

# Prerequisites

* Please download and install SWI-Prolog for your machine at `https://www.swi-prolog.org/build/`.

# 1. Install manually

Download <a href="http://github.com/luciangreen/LuciansHandBitMap-Font/">this repository</a>, the <a href="https://github.com/luciangreen/Languages">Languages repository</a> and <a href="https://github.com/luciangreen/culturaltranslationtool">Cultural Translation Tool</a>.

# 2. Or Install from List Prolog Package Manager (LPPM)

* Download the <a href="https://github.com/luciangreen/List-Prolog-Package-Manager">LPPM Repository</a>:

```
mkdir GitHub
cd GitHub/
git clone https://github.com/luciangreen/List-Prolog-Package-Manager.git
cd List-Prolog-Package-Manager
swipl
['lppm'].
lppm_install("luciangreen","LuciansHandBitMap-Font").
halt
```

# Running

* In Shell:
`cd LuciansHandBitMap-Font`
`swipl`

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

# Download Font

You may download <a href="https://www.fontspace.com/lucianshandbitmap-font-f30637">LuciansHandBitMap Font</a>.

# Authors

Lucian Green - Initial programmer - <a href="https://www.lucianacademy.com/">Lucian Academy</a>

# License

I licensed this project under the BSD3 License - see the LICENSE.md file for details
