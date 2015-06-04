## The SignWriting 2010 Fonts
- - - 
> Version 1.1.3  
June 4th, 2015

SignWriting 2010 is a typeface for written sign languages
which makes the entire [International SignWriting Alphabet 2010 symbol set][19] available in a TrueType font with OpenType features.

The SignWriting 2010 Fonts are built with the [SignWriting 2010 Tools][30].

The SignWriting 2010 Fonts are used in the [SignWriting 2010 JavaScript Library][60].

The SignWriting 2010 Fonts are highlighted in [SignMaker 2015][66].

### TrueType Fonts
The SignWriting 2010 Fonts are fully functional and production ready.  The image quality and glyph alignment has been perfected.

#### Installation
The TrueType Fonts can be installed on Linux, Windows, Mac, and iOS. 

- Reserved Font Name: [SignWriting 2010][57] with [log report][58]  
- Reserved Font Name: [SignWriting 2010 Filling][1] with [log report][2]  

Fonts packaged for iOS: [SignWriting 2010 Configuration Profile][61]

#### CSS Font-Face
The CSS Font-Face declaration works with all systems, regardless if the fonts are installed or not.  Use the CSS below with any HTML page to access the TrueType fonts.

When the TrueType fonts are not installed, the CSS Font-Face declaration will cause the browser to automatically download and install the fonts in the browser cache. The fonts are about 13 MB combined so the first page view will experience a slight delay while the fonts are downloaded and installed.  All subsequent page views, regardless of domain, will use the fonts that have already been installed in the browser cache without any additional delay.

When the TrueType fonts are installed on a system, the CSS Font-Face declaration will cause the browser to use the already installed local fonts and will not download the fonts from the URL.  When the fonts are installed, the CSS Font-Face isn't required but neither will it negatively affect performance.

    @font-face {
      font-family: "SignWriting 2010";
      src: 
        local('SignWriting 2010'),
        local('SignWriting_2010'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010.ttf') format('truetype');
    }
    @font-face {
      font-family: "SignWriting 2010 Filling";
      src: 
        local('SignWriting 2010 Filling'),
        local('SignWriting_2010_Filling'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Filling.ttf') format('truetype');
    }
### License
The SignWriting 2010 Fonts are free and open source.

>SignWriting 2010 Fonts  
Copyright (c) 1974-2015, Center for Sutton Movement Writing, inc  
Licensed under the [SIL Open Font License][24] v1.1


Original symbol design by Valerie Sutton.
Symbol image refinement in SVG by Adam Frost.
Encoding and transformation by Stephen E Slevinski Jr.

The SVGs of the compatibility glyphs for the character set "S1234567890abcdef" are based on [Source Sans Pro][25]
written by Paul D. Hunt and licensed under [SIL Open Font License][24], version 1.1.

### Demo Pages
The symbol demo pages can be created with the SignWriting 2010 Tools.
There are 3 types of demo pages available online.

* Unicode 8 demo pages: [view online][47] or [download][48]
* Unicode Private Use Area demo pages: [view online][49] or [download][50]
* Symbol Key demo pages: [view online][51] or [download][52]

Additionally, complete sign images with the TrueType fonts inside of SVGs is working nicely.  View the [codepen][59] example for a working demonstration.

- - - 

Source SVG
---------------
The source SVG required to build the TrueType fonts  is available in 2 data files.  These files were created with the SignWriting 2010 Tools by retracing the SVG Refinement.  These files can be unpacked with the SignWriting 2010 Tools.

* [SVG Line][55]  
* [SVG Filling][56]

- - -

Historical Formats
---------------------
The original font was created by Valerie Sutton as individual PNG files.  The SVG Refinement was a partnership of hand crafted SVGs by Adam Frost with automation tools  by Stephen E Slevinski Jr. 

These files can be unpacked with the SignWriting 2010 Tools.

* [Valerie Sutton's original PNG][53]
* [SVG Refinement][54]

- - -

Character Sets
--------------------
The various character sets used to access the symbol glyphs are Unicode compatible.  

1D800..1DAAF; Sutton SignWriting  
To be published in [Unicode 8][64] in [2015][22].  
Uses 1 to 3 characters per symbol.

FD800..FDFFF; SignWriting Text   
Private Use Area characters.  
Uses 3 characters per symbol.  Includes characters for structural markers and numbers.

100000...10FFFF; Symbol Code Points  
Private Use Area characters.  
Uses 1 character per symbol.

S10000..S38b07; ISWA 2010 Symbol Keys  
ASCII characters, UTF-8 compatible.  
[Symbol keys][19] used as glyph names in the font files.

The characters conversions implementation can be found in the [SignWriting 2010 JavaScript Library][60] in the "sw10.js" file under functions "uni8" for Unicode 8, "pua" for SignWriting Text characters on plane 15, and "code" for symbol code point characters on plane 16.  

The character encodings used in SignWriting 2010 are defined in an Internet Draft submitted to the IETF: [draft-slevinski-signwriting-text][26].
The document is improved and resubmitted every 6 months.
The character design has been stable since January 12, 2012.
The current version of the Internet Draft is 05.
The next version is planned for November 2015.

- - -

Epilogue
----------
This is a work in progress. Feedback, bug reports, and patches are welcomed.

- - -

To Do
-------
* Investigate symbol irregularities for the various browser/platform combinations.
* Fine tune symbol design where needed. 

Version History
------------------
* 1.1.3 - June 4th, 2015: added CSS font-face declaration
* 1.1.2 - May 20th, 2015: updated font links to CDN
* 1.1.1 - Feb 4th, 2015: updated character sets information
* 1.1 - Nov 10th, 2014: fine tuned glyphs for the SignWriting 2010 JavaScript library and added iOS support with config profile
* 1.0 - Oct 13th, 2014: production ready fonts
* 0.9.1 - Oct 11th, 2014: new sources and new TTFs
* 0.9 - Oct 3rd, 2014: added font test pages to readme
* 0.9 - Oct 2nd, 2014: Initial project with development TrueType fonts and source SVG.

[1]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Filling.ttf
[2]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Filling.log
[3]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Mono%20Filling.ttf
[4]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Mono%20Filling.log
[5]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Unified.ttf
[6]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Unified.log
[7]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Line.ttf
[8]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Line.log
[9]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Mono%20Unified.ttf
[10]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Mono%20Unified.log
[11]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Mono%20Line.ttf
[12]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010%20Mono%20Line.log
[13]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg1U.zip
[14]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg1L.zip
[15]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg1F.zip
[16]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svb1U.zip
[17]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svb1L.zip
[18]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svb1F.zip
[19]: http://signbank.org/iswa
[20]: http://signpuddle.net/iswa
[21]: http://www.unicode.org/alloc/Pipeline.html
[22]: http://unicode-inc.blogspot.com/2014/08/new-publication-schedule-for-unicode.html
[23]: http://tools.ietf.org/html/draft-slevinski-signwriting-text
[24]: http://scripts.sil.org/OFL
[25]: https://www.google.com/fonts/specimen/Source+Sans+Pro
[26]: http://tools.ietf.org/html/draft-slevinski-signwriting-text
[27]: http://signpuddle.net/iswa/swfont_test.html
[28]: http://signpuddle.net/iswa/swfonts.html
[29]: https://github.com/Slevinski/signwriting_2010_fonts
[30]: https://github.com/Slevinski/signwriting_2010_tools
[31]: https://github.com/Slevinski/swap
[32]: https://github.com/Slevinski/swis
[33]: https://signbank.org/swap
[34]: http://swis.wmflabs.org
[35]: http://signbank.org/swis
[36]: http://signpuddle.com
[37]: https://incubator.wikimedia.org/wiki/User:Slevinski
[38]: https://incubator.wikimedia.org/wiki/User:Slevinski/SignWriting/Incubator#SignWriting_Gadget
[39]: https://incubator.wikimedia.org/wiki/Wp/ase
[40]: https://incubator.wikimedia.org/wiki/Category:Incubator:Test_wikis_of_sign_languages
[41]: http://www.adobe.com/devnet/opentype/afdko/topic_feature_file_syntax.html#5.d
[42]: https://cdn.rawgit.com/Slevinski/signwriting_2010_tools/master/source/signwriting_2010_unicode8.fea
[43]: https://cdn.rawgit.com/Slevinski/signwriting_2010_tools/master/source/signwriting_2010_unicode_pua.fea
[44]: https://cdn.rawgit.com/Slevinski/signwriting_2010_tools/master/source/signwriting_2010_symbolkey.fea
[45]: http://fontforge.org/
[46]: http://fontforge.org/python.html
[47]: http://signpuddle.net/iswa/demo/unicode8
[48]: http://signpuddle.net/iswa/demo/unicode8.zip
[49]: http://signpuddle.net/iswa/demo/unicodepua
[50]: http://signpuddle.net/iswa/demo/unicodepua.zip
[51]: http://signpuddle.net/iswa/demo/symbolkey
[52]: http://signpuddle.net/iswa/demo/symbolkey.zip
[53]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/png_sutton.zip
[54]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg_refinement.zip
[55]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg_line.zip
[56]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/svg_fill.zip
[57]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010.ttf
[58]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010.log
[59]: http://codepen.io/Slevinski/pen/exnju
[60]: https://github.com/Slevinski/sw10js
[61]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SignWriting%202010.mobileconfig
[62]: http://github.com/Slevinski/sw10js
[63]: http://www.opensource.org/licenses/mit-license.php
[64]: http://www.unicode.org/versions/Unicode8.0.0/
[65]: https://cdn.rawgit.com/Slevinski/sw10js/gh-pages/sw10.js
[66]: http://github.com/Slevinski/signmaker