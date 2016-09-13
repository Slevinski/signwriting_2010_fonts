## The SignWriting 2010 Fonts
- - - 
> Version 2.0.1  
September 13th, 2016

SignWriting 2010 is a typeface for written sign languages which makes the entire [International SignWriting Alphabet 2010 symbol set][19] available in TrueType fonts.  

The Sutton SignWriting fonts are an updates revision of the SignWriting 2010 fonts which fixes the appearance and size for some of the symbols.  The fonts are built with the [SignWriting 2010 Tools][30].  The Sutton SignWriting Fonts are used in the [Sutton SignWriting Project][67].


### TrueType Fonts
The Sutton SignWriting fonts are fully functional and production ready.  
- Sutton SignWriting - the positive space of the symbol glyphs on plane 4
- Sutton SignWriting Fill - the negative space of the symbol glyphs on plane 16

#### Installation
The TrueType Fonts can be installed on Linux, Windows, Mac, and iOS. 

- Reserved Font Name: [Sutton SignWriting][68] with [log report][69]  
- Reserved Font Name: [Sutton SignWriting Fill][70] with [log report][71]  

Fonts packaged for iOS: [SignWriting 2010 Configuration Profile][72]

#### CSS Font-Face
The CSS Font-Face declaration works with all systems, regardless if the fonts are installed or not.  Use the CSS below with any HTML page to access the TrueType fonts.

When the TrueType fonts are not installed, the CSS Font-Face declaration will cause the browser to automatically download and install the fonts in the browser cache. The fonts are about 10 MB combined so the first page view will experience a slight delay while the fonts are downloaded and installed.  All subsequent page views, regardless of domain, will use the fonts that have already been installed in the browser cache without any additional delay.

When the TrueType fonts are installed on a system, the CSS Font-Face declaration will cause the browser to use the already installed local fonts and will not download the fonts from the URL.  When the fonts are installed, the CSS Font-Face isn't required but neither will it negatively affect performance.

    @font-face {
      font-family: "SuttonSignWriting";
      src: 
        local('SuttonSignWriting'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting.ttf') format('truetype');
    }
    @font-face {
      font-family: "SuttonSignWritingFill";
      src: 
        local('SuttonSignWritingFill'),
        url('https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf') format('truetype');
    }
### License
The Sutton SignWriting Fonts are free and open source.

>Sutton SignWriting Fonts  
Copyright (c) 1974-2016, Center for Sutton Movement Writing, inc  
Licensed under the [SIL Open Font License][24] v1.1


Original symbol design by Valerie Sutton.  
Symbol image refinement in SVG by Adam Frost.  
Encoding and transformation by Stephen E Slevinski Jr.


- - - 

Source SVG
---------------
The source SVG required to build the TrueType fonts  is available in 2 data files.  These files were created with the SignWriting 2010 Tools by retracing the SVG Refinement.  These files can be unpacked with the SignWriting 2010 Tools.  Each symbol has an explicit size listed in the [symsize.txt][75] file.

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

Unicode 8 Support
--------------------
1D800..1DAAF; Sutton SignWriting  
[Unicode 8][64] support without facial diacritic combining.  
Uses 1 to 3 characters per symbol.
- Reserved Font Name: [Sutton SignWriting 8][73] with [log report][74]  

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
[55]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/cae26de2d2c85aedd2940e1dab67c2c1294e6303/source/svg_line.zip
[56]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/cae26de2d2c85aedd2940e1dab67c2c1294e6303/source/svg_fill.zip
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
[67]: https://github.com/Slevinski/SuttonSignWriting
[68]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting.ttf
[69]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting.log
[70]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.ttf
[71]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWritingFill.log
[72]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting.mobileconfig
[73]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting8.ttf
[74]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/fonts/SuttonSignWriting8.log
[75]: https://cdn.rawgit.com/Slevinski/signwriting_2010_fonts/master/source/symsize.txt
