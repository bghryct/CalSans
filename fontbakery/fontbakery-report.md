## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[16] CalSans-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00B2 (SUPERSCRIPT TWO)

	- 0x00B3 (SUPERSCRIPT THREE)

	- 0x00B9 (SUPERSCRIPT ONE)
 
	- And 0x2074 (SUPERSCRIPT FOUR)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Cal Sans Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2278, but got 1660 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + i
	- i + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- ijacute 
	- And IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: uni1EA5	Contours detected: 3	Expected: 4
	- Glyph name: uni1EC1	Contours detected: 3	Expected: 4
	- Glyph name: uni1EE1	Contours detected: 2	Expected: 3
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: uni1EA5	Contours detected: 3	Expected: 4
	- Glyph name: uni1EC1	Contours detected: 3	Expected: 4 
	- And Glyph name: uni1EE1	Contours detected: 2	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* R (U+0052): X=552.0,Y=1402.0 (should be at cap-height 1400?)
	* sterling (U+00A3): X=710.0,Y=1.5 (should be at baseline 0?)
	* yen (U+00A5): X=-42.0,Y=1398.0 (should be at cap-height 1400?)
	* yen (U+00A5): X=1184.0,Y=1398.0 (should be at cap-height 1400?)
	* Atilde (U+00C3): X=288.5,Y=1658.0 (should be at ascender 1660?)
	* Atilde (U+00C3): X=814.0,Y=1658.0 (should be at ascender 1660?)
	* Ntilde (U+00D1): X=386.5,Y=1658.0 (should be at ascender 1660?)
	* Ntilde (U+00D1): X=912.0,Y=1658.0 (should be at ascender 1660?)
	* Otilde (U+00D5): X=414.5,Y=1658.0 (should be at ascender 1660?)
	* Otilde (U+00D5): X=940.0,Y=1658.0 (should be at ascender 1660?) and 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:
	* two (U+0032) contains a short segment L<<34.0,0.0>--<34.0,32.0>>
	* seven (U+0037) contains a short segment L<<1030.0,1400.0>--<1034.0,1370.0>>
	* at (U+0040) contains a short segment B<<1182.0,530.0>-<1179.0,511.0>-<1176.5,486.5>>
	* at (U+0040) contains a short segment B<<1176.5,486.5>-<1174.0,462.0>-<1174.0,444.0>>
	* Z (U+005A) contains a short segment L<<20.0,0.0>--<20.0,30.0>>
	* Z (U+005A) contains a short segment L<<1148.0,1400.0>--<1148.0,1370.0>>
	* z (U+007A) contains a short segment L<<28.0,0.0>--<28.0,30.0>>
	* z (U+007A) contains a short segment L<<946.0,1040.0>--<946.0,1010.0>>
	* onehalf (U+00BD) contains a short segment L<<894.0,50.0>--<894.0,70.0>>
	* Ccedilla (U+00C7) contains a short segment B<<644.0,-246.0>-<661.0,-261.0>-<680.5,-270.5>> and 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* exclam (U+0021): L<<154.0,386.0>--<108.0,1154.0>> -> L<<108.0,1154.0>--<108.0,1400.0>>
	* exclam (U+0021): L<<388.0,1400.0>--<388.0,1154.0>> -> L<<388.0,1154.0>--<342.0,386.0>>
	* exclamdbl (U+203C): L<<154.0,386.0>--<108.0,1154.0>> -> L<<108.0,1154.0>--<108.0,1400.0>>
	* exclamdbl (U+203C): L<<388.0,1400.0>--<388.0,1154.0>> -> L<<388.0,1154.0>--<342.0,386.0>>
	* exclamdbl (U+203C): L<<560.0,386.0>--<514.0,1154.0>> -> L<<514.0,1154.0>--<514.0,1400.0>>
	* exclamdbl (U+203C): L<<794.0,1400.0>--<794.0,1154.0>> -> L<<794.0,1154.0>--<748.0,386.0>>
	* exclamdown (U+00A1): L<<332.0,656.0>--<378.0,-112.0>> -> L<<378.0,-112.0>--<378.0,-358.0>>
	* exclamdown (U+00A1): L<<98.0,-358.0>--<98.0,-112.0>> -> L<<98.0,-112.0>--<144.0,656.0>>
	* ogonek (U+02DB): L<<784.0,34.0>--<870.0,12.0>> -> L<<870.0,12.0>--<942.0,0.0>>
	* uniA78B (U+A78B): L<<194.0,386.0>--<148.0,1154.0>> -> L<<148.0,1154.0>--<148.0,1400.0>> and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* eth (U+00F0): B<<599.0,941.5>-<646.0,925.0>-<679.0,899.0>>/B<<679.0,899.0>-<652.0,932.0>-<622.0,958.5>> = 12.476767960052687
	* r (U+0072): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* racute (U+0155): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* radical (U+221A): B<<424.0,-58.0>-<434.0,-106.0>-<439.0,-154.0>>/B<<439.0,-154.0>-<445.0,-107.0>-<452.0,-59.0>> = 13.221868011862771
	* rcaron (U+0159): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* rmacronbelow (U+1E5F): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* uni0157 (U+0157): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163 and uni1E5D (U+1E5D): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<1174.0,552.0>--<714.0,548.0>>
 * Gbreve (U+011E): L<<1174.0,552.0>--<714.0,548.0>>
 * Gcircumflex (U+011C): L<<1174.0,552.0>--<714.0,548.0>>
 * Gdotaccent (U+0120): L<<1174.0,552.0>--<714.0,548.0>>
 * R (U+0052): L<<100.0,1400.0>--<552.0,1402.0>>
 * Racute (U+0154): L<<100.0,1400.0>--<552.0,1402.0>>
 * Rcaron (U+0158): L<<100.0,1400.0>--<552.0,1402.0>>
 * Rmacronbelow (U+1E5E): L<<100.0,1400.0>--<552.0,1402.0>>
 * arrowdown (U+2193): L<<481.0,650.0>--<474.0,1458.0>>
 * arrowdown (U+2193): L<<726.0,1458.0>--<719.0,647.0>> and 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] CalSans-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00B2 (SUPERSCRIPT TWO)

	- 0x00B3 (SUPERSCRIPT THREE)

	- 0x00B9 (SUPERSCRIPT ONE)
 
	- And 0x2074 (SUPERSCRIPT FOUR)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Cal Sans Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2278, but got 1660 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + i
	- i + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- ijacute 
	- And IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: uni1EA5	Contours detected: 3	Expected: 4
	- Glyph name: uni1EC1	Contours detected: 3	Expected: 4
	- Glyph name: uni1EE1	Contours detected: 2	Expected: 3
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: uni1EA5	Contours detected: 3	Expected: 4
	- Glyph name: uni1EC1	Contours detected: 3	Expected: 4 
	- And Glyph name: uni1EE1	Contours detected: 2	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* R (U+0052): X=552.0,Y=1402.0 (should be at cap-height 1400?)
	* sterling (U+00A3): X=710.0,Y=1.5 (should be at baseline 0?)
	* yen (U+00A5): X=-42.0,Y=1398.0 (should be at cap-height 1400?)
	* yen (U+00A5): X=1184.0,Y=1398.0 (should be at cap-height 1400?)
	* Atilde (U+00C3): X=288.5,Y=1658.0 (should be at ascender 1660?)
	* Atilde (U+00C3): X=814.0,Y=1658.0 (should be at ascender 1660?)
	* Ntilde (U+00D1): X=386.5,Y=1658.0 (should be at ascender 1660?)
	* Ntilde (U+00D1): X=912.0,Y=1658.0 (should be at ascender 1660?)
	* Otilde (U+00D5): X=414.5,Y=1658.0 (should be at ascender 1660?)
	* Otilde (U+00D5): X=940.0,Y=1658.0 (should be at ascender 1660?) and 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:
	* two (U+0032) contains a short segment L<<34.0,0.0>--<34.0,32.0>>
	* seven (U+0037) contains a short segment L<<1030.0,1400.0>--<1034.0,1370.0>>
	* at (U+0040) contains a short segment B<<1182.0,530.0>-<1179.0,511.0>-<1176.5,486.5>>
	* at (U+0040) contains a short segment B<<1176.5,486.5>-<1174.0,462.0>-<1174.0,444.0>>
	* Z (U+005A) contains a short segment L<<20.0,0.0>--<20.0,30.0>>
	* Z (U+005A) contains a short segment L<<1148.0,1400.0>--<1148.0,1370.0>>
	* z (U+007A) contains a short segment L<<28.0,0.0>--<28.0,30.0>>
	* z (U+007A) contains a short segment L<<946.0,1040.0>--<946.0,1010.0>>
	* onehalf (U+00BD) contains a short segment L<<894.0,50.0>--<894.0,70.0>>
	* Ccedilla (U+00C7) contains a short segment B<<644.0,-246.0>-<661.0,-261.0>-<680.5,-270.5>> and 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* exclam (U+0021): L<<154.0,386.0>--<108.0,1154.0>> -> L<<108.0,1154.0>--<108.0,1400.0>>
	* exclam (U+0021): L<<388.0,1400.0>--<388.0,1154.0>> -> L<<388.0,1154.0>--<342.0,386.0>>
	* exclamdbl (U+203C): L<<154.0,386.0>--<108.0,1154.0>> -> L<<108.0,1154.0>--<108.0,1400.0>>
	* exclamdbl (U+203C): L<<388.0,1400.0>--<388.0,1154.0>> -> L<<388.0,1154.0>--<342.0,386.0>>
	* exclamdbl (U+203C): L<<560.0,386.0>--<514.0,1154.0>> -> L<<514.0,1154.0>--<514.0,1400.0>>
	* exclamdbl (U+203C): L<<794.0,1400.0>--<794.0,1154.0>> -> L<<794.0,1154.0>--<748.0,386.0>>
	* exclamdown (U+00A1): L<<332.0,656.0>--<378.0,-112.0>> -> L<<378.0,-112.0>--<378.0,-358.0>>
	* exclamdown (U+00A1): L<<98.0,-358.0>--<98.0,-112.0>> -> L<<98.0,-112.0>--<144.0,656.0>>
	* ogonek (U+02DB): L<<784.0,34.0>--<870.0,12.0>> -> L<<870.0,12.0>--<942.0,0.0>>
	* uniA78B (U+A78B): L<<194.0,386.0>--<148.0,1154.0>> -> L<<148.0,1154.0>--<148.0,1400.0>> and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* eth (U+00F0): B<<599.0,941.5>-<646.0,925.0>-<679.0,899.0>>/B<<679.0,899.0>-<652.0,932.0>-<622.0,958.5>> = 12.476767960052687
	* r (U+0072): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* racute (U+0155): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* radical (U+221A): B<<424.0,-58.0>-<434.0,-106.0>-<439.0,-154.0>>/B<<439.0,-154.0>-<445.0,-107.0>-<452.0,-59.0>> = 13.221868011862771
	* rcaron (U+0159): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* rmacronbelow (U+1E5F): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163
	* uni0157 (U+0157): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163 and uni1E5D (U+1E5D): L<<342.0,1040.0>--<342.0,842.0>>/B<<342.0,842.0>-<368.0,954.0>-<448.5,1013.0>> = 13.069317896282163 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<1174.0,552.0>--<714.0,548.0>>
 * Gbreve (U+011E): L<<1174.0,552.0>--<714.0,548.0>>
 * Gcircumflex (U+011C): L<<1174.0,552.0>--<714.0,548.0>>
 * Gdotaccent (U+0120): L<<1174.0,552.0>--<714.0,548.0>>
 * R (U+0052): L<<100.0,1400.0>--<552.0,1402.0>>
 * Racute (U+0154): L<<100.0,1400.0>--<552.0,1402.0>>
 * Rcaron (U+0158): L<<100.0,1400.0>--<552.0,1402.0>>
 * Rmacronbelow (U+1E5E): L<<100.0,1400.0>--<552.0,1402.0>>
 * arrowdown (U+2193): L<<481.0,650.0>--<474.0,1458.0>>
 * arrowdown (U+2193): L<<726.0,1458.0>--<719.0,647.0>> and 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 26 | 213 | 13 | 176 | 0 |
| 0% | 1% | 6% | 49% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
