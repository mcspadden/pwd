# pwd
simple password generator written in python


# Prerequisites

You will need python 3 installed to run **pwd**. Open up a CLI terminal then type `python -v` to see the current version installed. Go [here](https://docs.python.org/3/using/index.html "Python 3 documentation") for more information.

# Installing and Utilizing pwd
**Linux**
 * To install **pwd**, go to the main github page [here](https://github.com/mcspadden/pwd "pwd"). 
 * _Click_ **_Clone or Download_** > **_Download ZIP_**
 * _Navigate_ to the download location, _double-click_ the zip file to unzip it
 * Open up a **CLI terminal** > _Change_ the directory to the download location
   * **Example**: `cd /home/user/Downloads/pwd-Master`
 * Type the following commands:
  ```
  chmod +x pwd.py  
  python3 ./pwd.py
  ```
pwd is now successfully running. 
 
# Instructions

Once you start **pwd** and see `How many words you like the password to be? (1-30)`, type in a number between 1 and 30 then click _**Enter**_.
Type in `y` to make your password _all_ upper case or `n` to make your password _all_ lower case then click _**Enter**_. 

Your genererated password will now be printed. 

# Entropy
Information regarding entropy can be found [here](https://en.wikipedia.org/wiki/Entropy_(information_theory "Wikipedia: Entropy").  

You can calcuate your entropy [here](http://www.shannonentropy.netmark.pl/ "Shannon Entropy Calculator"). **DO NOT** generate a
password then go check your entropy _anywhere_ and continue utilizing that password. Generate a password with `x` number of words then
test the entropy. If you are satisfied, generate a new password with `x` the same as last time. 

# Quantum Effect
# License

I'm inspired by the world; so anything **I did** here, I want the world to be freely inspired by as well. For anything I did not create here, refer to their respective license for use.

# MIT License

Copyright (c) 2018 McSpadden

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
