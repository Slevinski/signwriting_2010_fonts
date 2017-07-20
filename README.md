## The SignWriting 2010 Fonts
- - - 
> Version 2.2.0  
July 20th, 2017

SignWriting 2010 is a typeface for written sign languages which makes the entire [International SignWriting Alphabet 2010 symbol set](http://signbank.org/iswa) available in TrueType fonts.  

The Sutton SignWriting fonts are an updates revision of the SignWriting 2010 fonts which fixes the appearance and size for some of the symbols.  
The fonts are built with the [SignWriting 2010 Tools](https://github.com/Slevinski/signwriting_2010_tools).  The Sutton SignWriting Fonts are used in the [Sutton SignWriting Project](https://github.com/Slevinski/SuttonSignWriting).


### TrueType Fonts
The Sutton SignWriting TrueType fonts are available for download and installation.  

#### Symbol Fonts for SVG  
There are two fonts for the Sutton SignWriting symbols that are used in SVG: the Sutton SignWriting Line font as the positive space of the symbol glyphs on Unicode plane 15 and the Sutton SignWriting Fill font as the negative space of the symbol glyphs on Unicode plane 16. These glyphs descend below the baseline. 

* [SuttonSignWritingLine.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.ttf) - the positive space of the symbol glyphs on Unicode plane 15
* [SuttonSignWritingFill.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf) - the negative space of the symbol glyphs on Unicode plane 16

#### 1 Dimensional Font for Unicode Option 1
The Sutton SignWriting 1D Optimal font visualizes a Formal SignWriting word as a 1-dimensional string of glyphs for structural markers, symbols, and numbers. The font uses the Unicode Option 1 character set. These glyphs are centered above the baseline and are meant to be used in traditionally 1-dimensional situations. 

* [SuttonSignWriting1dOpt.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1dOpt.ttf)

#### 1 Dimensional Font for Unicode Option 2  
The Sutton SignWriting 1D font visualizes a Formal SignWriting word as a 1-dimensional string of glyphs for structural markers, symbols, and numbers. The font uses the Unicode Option 2 character set. These glyphs are centered above the baseline and are meant to be used in traditionally 1-dimensional situations.

Using this font requires the support of the ligature feature "ccmp" for Glyph Composition/Decomposition. Support in older software is limited. In the browser, "ccmp" ligatures support with extension lookup is sometimes possible, but it will require extra css to define the font famiily and may require extra css to enable the "ccmp" feature. 

* [SuttonSignWriting1d.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1d.ttf)

#### Installation
The TrueType Fonts can be installed on Linux, Windows, and Mac.  For iOS, a configuration profile can be created using any or all of the files below. 

- Reserved Font Name: [Sutton SignWriting Line](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.log)  
- Reserved Font Name: [Sutton SignWriting Fill](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.log)  
- Reserved Font Name: [Sutton SignWriting 1D Optimal](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1dOpt.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1dOpt.log)  
- Reserved Font Name: [Sutton SignWriting 1D](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1d.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1d.log)  


#### CSS Font-Face
The CSS Font-Face declaration works with all systems, regardless if the fonts are installed or not.  Use the CSS below with any HTML page to access the TrueType fonts.

When the TrueType fonts are not installed, the CSS Font-Face declaration will cause the browser to automatically download and install the fonts in the browser cache. The fonts range from 2.5 MB to 9 MB each so the first page view will experience a slight delay while the fonts are downloaded and installed.  All subsequent page views, regardless of domain, will use the fonts that have already been installed in the browser cache without any additional delay.

When the TrueType fonts are installed on a system, the CSS Font-Face declaration will cause the browser to use the already installed local fonts and will not download the fonts from the URL.  When the fonts are installed, the CSS Font-Face isn't required but neither will it negatively affect performance.

    @font-face {
      font-family: "SuttonSignWritingLine";
      src: 
        local('SuttonSignWritingLine'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.ttf') format('truetype');
    }
    @font-face {
      font-family: "SuttonSignWritingFill";
      src: 
        local('SuttonSignWritingFill'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf') format('truetype');
    }
    @font-face {
      font-family: "SuttonSignWriting1dOpt";
      src: 
        local('SuttonSignWriting1dOpt'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1dOpt.ttf') format('truetype');
    }
    @font-face {
      font-family: "SuttonSignWriting1d";
      src: 
        local('SuttonSignWriting1d'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting1d.ttf') format('truetype');
    }
### License
The Sutton SignWriting Fonts are free and open source.

>Sutton SignWriting Fonts  
Copyright (c) 1974-2017, Center for Sutton Movement Writing, inc  
Licensed under the [SIL Open Font License](http://scripts.sil.org/OFL) v1.1


Original symbol design by Valerie Sutton.  
Symbol image refinement in SVG by Adam Frost.  
Encoding and transformation by Stephen E Slevinski Jr.


- - - 

Source SVG
---------------
The source SVG required to build the TrueType fonts  is available in 2 data files.  These files were created with the SignWriting 2010 Tools by retracing the SVG Refinement.  These files can be unpacked with the SignWriting 2010 Tools.  Each symbol has an explicit size listed in the source/symsize.txt file.

* [SVG Line](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/cae26de2d2c85aedd2940e1dab67c2c1294e6303/source/svg_line.zip)  
* [SVG Filling](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/cae26de2d2c85aedd2940e1dab67c2c1294e6303/source/svg_fill.zip)  


- - -

Deprecated
---------------------
The original SuttonSignWriting.ttf used plane 4 for the symbol line in SVG with glyphs that are below the baseline.  This conflicted with the 1D and 2D font designs.  This font has been replaced with "SuttonSignWritingLine.ttf" on plane 15.

- Reserved Font Name: [Sutton SignWriting](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting.log)  

- - -

Historical Formats
---------------------
The original font was created by Valerie Sutton as individual PNG files.  The SVG Refinement was a partnership of hand crafted SVGs by Adam Frost with automation tools  by Stephen E Slevinski Jr. 

These files can be unpacked with the SignWriting 2010 Tools.

* [Valerie Sutton's original PNG](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/png_sutton.zip)
* [SVG Refinement](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg_refinement.zip)

- - -

Unicode 8 Support
--------------------
1D800..1DAAF; Sutton SignWriting  
[Unicode 8](http://www.unicode.org/versions/Unicode8.0.0/) support without facial diacritic combining.  
Uses 1 to 3 characters per symbol.
- Reserved Font Name: [Sutton SignWriting 8](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting8.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting8.ttf)  

- - -

Epilogue
----------
This is a work in progress. Feedback, bug reports, and patches are welcomed.

- - -

To Do
-------
* 2-dimensional layout within font

Version History
------------------
* 2.2.0 - July 20th, 2017: added SuttonSignWritingLine on plane 15
* 2.1.0 - June 29th, 2017: added 1-D fonts for Unicode options 1 and 2
* 2.0.1 - Sept 13th, 2016: updated source links
* 2.0.0 - Sept 13th, 2016: Sutton SignWriting fonts improvement
* 1.1.4 - June 26th, 2015: no facial diacritic combining
* 1.1.3 - June 4th, 2015: added CSS font-face declaration
* 1.1.2 - May 20th, 2015: updated font links to CDN
* 1.1.1 - Feb 4th, 2015: updated character sets information
* 1.1 - Nov 10th, 2014: fine tuned glyphs for the SignWriting 2010 JavaScript library and added iOS support with config profile
* 1.0 - Oct 13th, 2014: production ready fonts
* 0.9.1 - Oct 11th, 2014: new sources and new TTFs
* 0.9 - Oct 3rd, 2014: added font test pages to readme
* 0.9 - Oct 2nd, 2014: Initial project with development TrueType fonts and source SVG.
