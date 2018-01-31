## The SignWriting 2010 Fonts
- - - 
> Version 3.0.2  
January 31th, 2018  
License: SIL Open Font License 1.1

SignWriting 2010 is a typeface for written sign languages which makes the entire [International SignWriting Alphabet 2010 symbol set](http://signbank.org/iswa) available in TrueType fonts.  

The Sutton SignWriting fonts are an updated revision of the SignWriting 2010 fonts which fixes the appearance and size for some of the symbols.  

The Sutton SignWriting Fonts are used in the [Sutton SignWriting Project](https://github.com/Slevinski/SuttonSignWriting) and in [SignMaker](https://github.com/Slevinski/signmaker).

The fonts are built with the [SignWriting 2010 Tools](https://github.com/Slevinski/signwriting_2010_tools).

### Character Sets

#### FSW - Formal SignWriting in ASCII
Signs are written as SignWriting words with mathamatical names of ASCII characters from the set: ABLMRS0123456789xabcdef.  Stable since January 2012.

#### SWU - SignWriting in Unicode
Signs are written as SignWriting words with an experimental Unicode character design.  This character set overwrites the Sutton SignWriting Block (U+1D800 - U+1D9FF) and uses Plane 4 for the Sutton SignWriting symbols.

### TrueType Fonts
The Sutton SignWriting TrueType fonts are available for download and installation.  

#### Symbol Fonts for SVG  
There are two fonts for the Sutton SignWriting symbols that are used in SVG: the Sutton SignWriting Line font as the positive space of the symbol glyphs on Unicode plane 15 and the Sutton SignWriting Fill font as the negative space of the symbol glyphs on Unicode plane 16. These glyphs descend below the baseline. 

* [SuttonSignWritingLine.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.ttf) - the positive space of the symbol glyphs on Unicode plane 15
* [SuttonSignWritingFill.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf) - the negative space of the symbol glyphs on Unicode plane 16

#### One Dimensional Font for SignWriting in Unicode
The Sutton SignWriting One-D font is production ready.  It uses the SignWriting in Unicode (SWU) characters to visualizes a sign as a 1-dimensional string of glyphs for structural markers, symbols, and numbers.  These glyphs are centered above the baseline and are meant to be used in traditionally 1-dimensional situations.

* [SuttonSignWritingOneD.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingOneD.ttf)

#### Two Dimensional Font for SignWriting in Unicode  
The Sutton SignWriting Two-D font is in development.  It will use the SignWriting in Unicode characters with the Universal Shaping Engine to correctly display a sign as a 2-dimensional cluster of symbols glyphs. 

* [Sutton SignWriting Two-D Font Project](https://meta.wikimedia.org/wiki/Grants:Project/slevinski/ASL_Wikipedia_2-D_Font_Development_for_SignWriting)

#### Sutton SignWriting Null  
The Sutton SignWriting Null font provides empty glyphs for invalid symbol codes on Plane 4 and Plane 15.  The font is useful to normalize how browsers and software process invalid characters.

* [SuttonSignWritingNull.ttf](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingNull.ttf)

### Installation
The TrueType Fonts can be installed on Linux, Windows, and Mac.  For Mac OS and iOS, a configuration profile can be created with the fonts below. 

- Reserved Font Name: [Sutton SignWriting Line](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingLine.log)  
- Reserved Font Name: [Sutton SignWriting Fill](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.log)  
- Reserved Font Name: [Sutton SignWriting One D](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingOneD.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingOneD.log)  
- Reserved Font Name: [Sutton SignWriting Null](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingNull.ttf) with [log report](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingNull.log)  

#### Windows, Linux, and Mac

Installation is straight forward for these platforms. Simply download the TrueType fonts and install as usual.  

#### Mac and iOS

Installation is possible for Mac OS and iOS with two configuration profiles. The Sutton SignWriting Symbol profile and the Sutton SignWriting One profile. 

##### Sutton SignWriting Symbol (configuration profile)
The Sutton SignWriting Symbol configuration profile contains two fonts for use in SVG, the HTML Canvas, and other Cartesian Coordinate based systems.

The Sutton SignWriting Line Font contains glyphs for the positive space of the symbol images with characters on Unicode plane 15.

The Sutton SignWriting Fill Font contains glyphs for the negative space of the symbol images with characters on Unicode plane 16.

- [Sutton SignWriting Symbol (configuration profile)](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingSymbol.mobileconfig)  

##### Sutton SignWriting One (configuration profile)
The Sutton SignWriting One configuration profile contains two fonts for use in text input and for rendering normalization.

The Sutton SignWriting One D Font contains glyphs for symbols, markers, and numbers for use in traditional one dimensional text using SWU as an experimental Unicode design.

The Sutton SignWriting Null Font contains empty glyphs for invalid symbol codes on Plane 4 and Plane 15. This font is useful to normalize how browsers and software process invalid characters.

* [Sutton SignWriting One (configuration profile)](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingOne.mobileconfig)  

#### Android

Android can not install the fonts directly onto the system. The CSS declarations below will install the fonts in the browser cache. 

### CSS Font-Face
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
      font-family: "SuttonSignWritingOneD";
      src: 
        local('SuttonSignWritingOneD'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingOneD.ttf') format('truetype');
    }
    @font-face {
      font-family: "SuttonSignWritingNull";
      src: 
        local('SuttonSignWritingNull'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingNull.ttf') format('truetype');
    }

- - - 

### Source SVG
Original symbol design by Valerie Sutton.  
Symbol image refinement in SVG by Adam Frost.  
Encoding and transformation by Stephen E Slevinski Jr.  

The source SVG required to build the TrueType fonts  is available in 2 data files.  These files were created with the SignWriting 2010 Tools by retracing the SVG Refinement.  These files can be unpacked with the SignWriting 2010 Tools.  Each symbol has an explicit size listed in the source/symsize.txt file.

* [SVG Line](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/cae26de2d2c85aedd2940e1dab67c2c1294e6303/source/svg_line.zip)  
* [SVG Filling](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/cae26de2d2c85aedd2940e1dab67c2c1294e6303/source/svg_fill.zip)  

- - -

### Deprecated
The original SuttonSignWriting.ttf used plane 4 for the symbol line in SVG with glyphs that are below the baseline.  This conflicted with the 1D and 2D font designs.  This font has been replaced with "SuttonSignWritingLine.ttf" on plane 15.

- Reserved Font Name: Sutton SignWriting font (SuttonSignWriting.ttf)

- - -

The SuttonSignWriting8.ttf included partial support for the SignWriting in Unicode 8 design: 1D800..1DAAF; Sutton SignWriting.  The font does not support facial diacritics and uses 1 to 3 characters per Sutton SignWriting symbol.  The font has serious issues and limited use.  It has been discontinued.

- Reserved Font Name: Sutton SignWriting font (SuttonSignWriting8.ttf)

---

The SuttonSignWriting1d.ttf font add 17 characters to the SignWriting in Unicode 8 design to fully support writing a sign as a string of Unicode characters.  It has serious issues with limited use.  It has been discontinued.

- Reserved Font Name: Sutton SignWriting 1D (SuttonSignWriting1d.ttf)

---

The Sutton SignWriting 1D Optimal font has been replaced with the Sutton SignWriting One-D font.

- Reserved Font Name: Sutton SignWriting 1D Optimal (SuttonSignWriting1dOpt.ttf)

---


The Sutton SignWriting configuration profile (SuttonSignWriting.mobileconfig) and the Sutton SignWriting Plus configuration profile (SuttonSignWritingPlus.mobileconfig) both include deprecated fonts.  These profiles have been replaced with the Sutton SignWriting Symbol configuration profile (SuttonSignWritingSymbol.mobileconfig) and the Sutton SignWriting One configuration profile (SuttonSignWritingOne.mobileconfig).
- - -

### Historical Formats
The original font was created by Valerie Sutton as individual PNG files.  The SVG Refinement was a partnership of hand crafted SVGs by Adam Frost with automation tools  by Stephen E Slevinski Jr. 

These files can be unpacked with the SignWriting 2010 Tools.

* [Valerie Sutton's original PNG](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/png_sutton.zip)
* [SVG Refinement](https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg_refinement.zip)

- - -

### Epilogue
This is a work in progress. Feedback, bug reports, and patches are welcomed.

- - -

### To Do
* 2-dimensional layout within font

- - -

### Version History
* 3.0.2 - Jan 31th, 2017: Improved license declaration
* 3.0.1 - Aug 27th, 2017: Restored deprecated fonts 
* 3.0.0 - Aug 26th, 2017: SignWriting in Unicode characters and updated fonts
* 2.2.1 - July 24th, 2017: added SuttonSignWritingPlus.mobileconfig
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
