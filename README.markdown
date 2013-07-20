Bidi Less Boilerplate
=============================

Bidirectional Boilerplate CSS written in [Less.CSS](http://lesscss.org/), the dynamic stylesheet language. It includes: 

- Improved CSS Reset
- Some default styles
- Bidi Mixins that will reverse all right/left styles via @rtl variable
--- direction
--- float
--- clear
--- padding
--- margin
--- background-position
--- border
--- text
--- align
- Crossbrowser CSS3 and Short-Code Mixins (with old IE support)
--- font : converts font-size to EM unit, easy to specify family,size,line-height & weight together
--- opacity
--- border-radius
--- box-shadow
--- user-select
--- transition
--- rgba
--- gradient

We used original boilerplate project then for some Multilingual project that included Bidirectional Languages that needed "direction: rtl", we added Bidi Mixins to easily switch between RTL/LTR mode and compile two different CSS with reversed layout using one .LESS resource


Demo
---------
Coming Soon

Usage
--------
Include this file in at the top of your LESS stylesheet:

    @import 'boilerplate';

Enjoy!

License
--------
The MIT License

Copyright (c) 2011 Michael P. Geraci

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.