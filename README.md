The SignWriting 2010 Fonts
=====================
- - - 
> Version 0.9  
October 2nd, 2014

SignWriting 2010 is a typeface for written sign languages
which makes the entire [International SignWriting Alphabet 2010 symbol set][19] available in a TrueType font with OpenType features.

Fonts
-------
The SignWriting 2010 Fonts are fully functional but not production ready.  

There are several issues with sizing and alignment for the various glyphs.  The font settings and the individual glyph settings can be adjusted in the SignWriting 2010 Tools project and the fonts can quickly be recreated.

There are a few issues regarding the image quality.  Overall, the TrueType quality is very close to the SVG, but there are obvious differences when the images are zoomed.  There are a handful of symbols that need to be adjusted by hand because the SVG import failed to produce a legible glyph.  These issues will be resolved before the 1.0 release.


### Public TrueType Fonts  
> Reserved Font Name: SignWriting 2010  
Reserved Font Name: [SignWriting 2010 Filling][1] with [log report][2]  
Reserved Font Name: SignWriting 2010 Mono  
Reserved Font Name: [SignWriting 2010 Mono Filling][3] with [log report][4]  

### Development Fonts  
> Reserved Font Name: [SignWriting 2010 Unified][5] with [log report][6]  
Reserved Font Name: [SignWriting 2010 Line][7] with [log report][8]  
Reserved Font Name: SignWriting 2010 Other  
Reserved Font Name: [SignWriting 2010 Mono Unified][9] with [log report][10]  
Reserved Font Name: [SignWriting 2010 Mono Line][11] with [log report][12]  
Reserved Font Name: SignWriting 2010 Other

### License
The SignWriting 2010 Fonts are free and open source, released under
[SIL Open Font License][24], version 1.1.

Original symbol design by Valerie Sutton.
Symbol image refinement in SVG by Adam Frost.
Encoding and transformation by Stephen E Slevinski Jr.

The SVGs of the compatibility glyphs for the character set "S1234567890abcdef" are based on [Source Sans Pro][25]
written by Paul D. Hunt and licensed under [SIL Open Font License][24], version 1.1.

- - - 

Source SVG
--------------
The SignWriting 2010 Fonts are created from individual SVG files.  The SVG files are available in the following zipped directories.  The SVG files are based on the [ISWA 2010 Font Reference][20] version 1.10.1.

### Individually Sized SVG
> [SVG1 Unified Glyphs][13]  
[SVG1 Line Glyphs][14]  
[SVG1 Filling Glyphs][15]  
SVG1 Other Glyphs  

### Mono Sized SVG with viewBox

> [SVG1 Unified Glyphs][16]  
[SVG1 Line Glyphs][17]  
[SVG1 Filling Glyphs][18]  
SVG1 Other Glyphs
  
- - -

Character Sets
--------------------
Three different character sets can be used to access the glyphs.

1D800..1DAAF; Sutton SignWriting  
To be published in [Unicode 8][21] in [2015][22].

FD800..FDFFF; SignWriting Text  
[Private Use Area characters][26] for 2-dimensional text.

S10000..S38b07; ISWA 2010 Symbol Keys  
[Symbol keys][19] used as glyph names in the font files.

The character encodings used in SignWriting 2010 are defined in an Internet Draft submitted to the IETF: [draft-slevinski-signwriting-text][26].
The document is improved and resubmitted every 6 months.
The character design has been stable since January 12, 2012.
The current version of the Internet Draft is 03.
The next version is planned for November 2014.

- - -

Epilogue
----------
This is a work in progress. Feedback, bug reports, and patches are welcomed.

- - -

To Do
-------
* Improve the fonts and release new versions
* Create new source SVG called `SVG1 Other Glyphs` for the SignWriting 2010 Tools project
* Create demo pages that show the font usage

Version History
------------------
* 0.9 - Oct 2nd, 2014: Initial project with development TrueType fonts and source SVG.

[1]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Filling.ttf
[2]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Filling.log
[3]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Mono%20Filling.ttf
[4]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Mono%20Filling.log
[5]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Unified.ttf
[6]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Unified.log
[7]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Line.ttf
[8]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Line.log
[9]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Mono%20Unified.ttf
[10]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Mono%20Unified.log
[11]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Mono%20Line.ttf
[12]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/fonts/SignWriting%202010%20Mono%20Line.log
[13]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/source/svg1U.zip
[14]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/source/svg1L.zip
[15]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/source/svg1F.zip
[16]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/source/svb1U.zip
[17]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/source/svb1L.zip
[18]: https://github.com/Slevinski/signwriting_2010_fonts/raw/master/source/svb1F.zip
[19]: http://signbank.org/iswa
[20]: http://signpuddle.net/iswa
[21]: http://www.unicode.org/alloc/Pipeline.html
[22]: http://unicode-inc.blogspot.com/2014/08/new-publication-schedule-for-unicode.html
[23]: http://tools.ietf.org/html/draft-slevinski-signwriting-text
[24]: http://scripts.sil.org/OFL
[25]: https://www.google.com/fonts/specimen/Source+Sans+Pro
[26]: http://tools.ietf.org/html/draft-slevinski-signwriting-text
