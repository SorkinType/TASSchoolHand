## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[20] TASSchoolHand-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Medium'. Expected OS/2 usWeightClass is 500, got 540. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "TASSchoolHand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 965, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, malayalam, math, coptic, canadian-aboriginal, syriac, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _part.c.out.fin

	- _part.e.cv05.alt

	- e.init

	- grave.001

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tilde.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 913 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 824:
less

Width = 914:
equal, greaterequal, notequal

Width = 825:
greater

Width = 931:
plusminus

Width = 896:
multiply

Width = 898:
approxequal

Width = 915:
lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=903.5,Y=2006.5 (should be at cap-height 2008?)

	* period (U+002E): X=48.0,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=48.0,Y=-1.0 (should be at baseline 0?)

	* four (U+0034): X=825.0,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=1629.5,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=84.0,Y=-1.0 (should be at baseline 0?)

	* Y (U+0059): X=437.0,Y=-1.0 (should be at baseline 0?)

	* section (U+00A7): X=815.0,Y=2009.0 (should be at cap-height 2008?)

	* section (U+00A7): X=1057.0,Y=2009.0 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=437.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=269.0,Y=-2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=627.0,Y=2010.0 (should be at cap-height 2008?)

	* Eng (U+014A): X=144.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=144.0,Y=1.0 (should be at baseline 0?)

	* eng (U+014B): X=160.0,Y=1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=247.0,Y=-2.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=437.0,Y=-1.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=437.0,Y=-1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=827.0,Y=-1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=613.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=827.0,Y=-1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=437.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment B<<381.0,1609.5>-<358.0,1621.0>-<344.0,1638.0>>

	* three (U+0033) contains a short segment B<<47.0,596.0>-<74.0,604.0>-<96.0,604.0>>

	* three (U+0033) contains a short segment B<<1341.0,1913.0>-<1341.0,1887.0>-<1331.0,1867.5>>

	* five (U+0035) contains a short segment B<<394.5,990.5>-<375.0,985.0>-<352.0,985.0>>

	* G (U+0047) contains a short segment B<<1258.5,1028.0>-<1278.0,1055.0>-<1296.5,1062.0>>

	* G (U+0047) contains a short segment B<<1296.5,1062.0>-<1315.0,1069.0>-<1340.0,1069.0>>

	* K (U+004B) contains a short segment B<<1535.0,1999.0>-<1563.0,2008.0>-<1583.0,2008.0>>

	* M (U+004D) contains a short segment B<<1890.0,1991.0>-<1923.0,2008.0>-<1970.0,2008.0>>

	* M (U+004D) contains a short segment B<<1663.0,85.0>-<1656.0,53.0>-<1634.5,26.5>>

	* M (U+004D) contains a short segment B<<1550.0,0.0>-<1506.0,0.0>-<1483.5,21.5>>

	* M (U+004D) contains a short segment B<<1483.5,21.5>-<1461.0,43.0>-<1455.0,73.5>>

	* M (U+004D) contains a short segment B<<1455.0,73.5>-<1449.0,104.0>-<1456.0,130.0>>

	* M (U+004D) contains a short segment B<<957.0,69.0>-<936.0,34.0>-<905.5,17.0>>

	* M (U+004D) contains a short segment B<<905.5,17.0>-<875.0,0.0>-<841.0,0.0>>

	* M (U+004D) contains a short segment B<<264.0,96.0>-<255.0,57.0>-<228.0,28.5>>

	* N (U+004E) contains a short segment B<<704.0,1981.5>-<734.0,1955.0>-<741.0,1928.0>>

	* N (U+004E) contains a short segment B<<1090.0,20.5>-<1062.0,41.0>-<1053.0,72.0>>

	* R (U+0052) contains a short segment B<<1183.0,0.0>-<1161.0,0.0>-<1139.0,13.5>>

	* Z (U+005A) contains a short segment B<<44.5,12.5>-<18.0,25.0>-<10.0,36.0>>

	* k (U+006B) contains a short segment B<<806.0,0.0>-<786.0,0.0>-<767.0,8.0>>

	* Ntilde (U+00D1) contains a short segment B<<704.0,1981.5>-<734.0,1955.0>-<741.0,1928.0>>

	* Ntilde (U+00D1) contains a short segment B<<1090.0,20.5>-<1062.0,41.0>-<1053.0,72.0>>

	* oslash (U+00F8) contains a short segment L<<626.0,906.0>--<623.0,907.0>>

	* Gbreve (U+011E) contains a short segment B<<1258.5,1028.0>-<1278.0,1055.0>-<1296.5,1062.0>>

	* Gbreve (U+011E) contains a short segment B<<1296.5,1062.0>-<1315.0,1069.0>-<1340.0,1069.0>>

	* Gdotaccent (U+0120) contains a short segment B<<1258.5,1028.0>-<1278.0,1055.0>-<1296.5,1062.0>>

	* Gdotaccent (U+0120) contains a short segment B<<1296.5,1062.0>-<1315.0,1069.0>-<1340.0,1069.0>>

	* uni0122 (U+0122) contains a short segment B<<1258.5,1028.0>-<1278.0,1055.0>-<1296.5,1062.0>>

	* uni0122 (U+0122) contains a short segment B<<1296.5,1062.0>-<1315.0,1069.0>-<1340.0,1069.0>>

	* uni0136 (U+0136) contains a short segment B<<1535.0,1999.0>-<1563.0,2008.0>-<1583.0,2008.0>>

	* uni0137 (U+0137) contains a short segment B<<806.0,0.0>-<786.0,0.0>-<767.0,8.0>>

	* Nacute (U+0143) contains a short segment B<<704.0,1981.5>-<734.0,1955.0>-<741.0,1928.0>>

	* Nacute (U+0143) contains a short segment B<<1090.0,20.5>-<1062.0,41.0>-<1053.0,72.0>>

	* uni0145 (U+0145) contains a short segment B<<704.0,1981.5>-<734.0,1955.0>-<741.0,1928.0>>

	* uni0145 (U+0145) contains a short segment B<<1090.0,20.5>-<1062.0,41.0>-<1053.0,72.0>>

	* Ncaron (U+0147) contains a short segment B<<704.0,1981.5>-<734.0,1955.0>-<741.0,1928.0>>

	* Ncaron (U+0147) contains a short segment B<<1090.0,20.5>-<1062.0,41.0>-<1053.0,72.0>>

	* Racute (U+0154) contains a short segment B<<1183.0,0.0>-<1161.0,0.0>-<1139.0,13.5>>

	* uni0156 (U+0156) contains a short segment B<<1183.0,0.0>-<1161.0,0.0>-<1139.0,13.5>>

	* Rcaron (U+0158) contains a short segment B<<1183.0,0.0>-<1161.0,0.0>-<1139.0,13.5>>

	* Zacute (U+0179) contains a short segment B<<44.5,12.5>-<18.0,25.0>-<10.0,36.0>>

	* Zdotaccent (U+017B) contains a short segment B<<44.5,12.5>-<18.0,25.0>-<10.0,36.0>>

	* Zcaron (U+017D) contains a short segment B<<44.5,12.5>-<18.0,25.0>-<10.0,36.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<613.0,1.0>-<586.0,1.0>-<550.0,20.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1884.0,1949.0>-<1894.0,1927.0>-<1890.0,1895.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1890.0,1895.0>-<1886.0,1863.0>-<1861.0,1834.0>>

	* Euro (U+20AC) contains a short segment B<<1393.0,598.0>-<1393.0,585.0>-<1379.5,550.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* A (U+0041): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* AE (U+00C6): L<<952.0,1734.0>--<853.0,1488.0>> -> L<<853.0,1488.0>--<682.0,1149.0>>

	* AE (U+00C6): L<<979.0,1149.0>--<952.0,1477.0>> -> L<<952.0,1477.0>--<952.0,1734.0>>

	* Aacute (U+00C1): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Aacute (U+00C1): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Abreve (U+0102): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Abreve (U+0102): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Acircumflex (U+00C2): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Acircumflex (U+00C2): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Adieresis (U+00C4): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Adieresis (U+00C4): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Agrave (U+00C0): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Agrave (U+00C0): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Amacron (U+0100): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Amacron (U+0100): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Aogonek (U+0104): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Aogonek (U+0104): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Aring (U+00C5): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Aring (U+00C5): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* Atilde (U+00C3): L<<1071.0,1110.0>--<1073.0,1382.0>> -> L<<1073.0,1382.0>--<1092.0,1703.0>>

	* Atilde (U+00C3): L<<1092.0,1703.0>--<932.0,1388.0>> -> L<<932.0,1388.0>--<769.0,1110.0>>

	* oslash (U+00F8): L<<303.0,247.0>--<456.0,535.0>> -> L<<456.0,535.0>--<626.0,906.0>>

	* oslash (U+00F8): L<<726.0,821.0>--<540.0,486.0>> -> L<<540.0,486.0>--<401.0,175.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] TASSchoolHand-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "TASSchoolHand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 965, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, malayalam, math, coptic, canadian-aboriginal, syriac, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _part.c.out.fin

	- _part.e.cv05.alt

	- e.init

	- grave.001

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tilde.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 996 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 994:
plus, minus, divide

Width = 898:
less

Width = 900:
greater

Width = 1030:
plusminus

Width = 955:
multiply

Width = 962:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=1194.0,Y=1.0 (should be at baseline 0?)

	* Q (U+0051): X=778.0,Y=1.0 (should be at baseline 0?)

	* X (U+0058): X=624.0,Y=2008.5 (should be at cap-height 2008?)

	* b (U+0062): X=673.5,Y=1082.5 (should be at x-height 1082?)

	* g (U+0067): X=495.0,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=495.0,Y=1.5 (should be at baseline 0?)

	* t (U+0074): X=802.0,Y=1081.5 (should be at x-height 1082?)

	* u (U+0075): X=174.0,Y=-1.5 (should be at baseline 0?)

	* y (U+0079): X=194.0,Y=-1.0 (should be at baseline 0?)

	* y (U+0079): X=1017.0,Y=1081.0 (should be at x-height 1082?)

	* yen (U+00A5): X=1569.5,Y=2006.0 (should be at cap-height 2008?)

	* Atilde (U+00C3): X=941.5,Y=2574.0 (should be at ascender 2576?)

	* Atilde (U+00C3): X=1113.5,Y=2575.5 (should be at ascender 2576?)

	* Ntilde (U+00D1): X=1003.5,Y=2574.0 (should be at ascender 2576?)

	* Ntilde (U+00D1): X=1175.5,Y=2575.5 (should be at ascender 2576?)

	* Otilde (U+00D5): X=947.5,Y=2574.0 (should be at ascender 2576?)

	* Otilde (U+00D5): X=1119.5,Y=2575.5 (should be at ascender 2576?)

	* germandbls (U+00DF): X=1137.0,Y=2007.0 (should be at cap-height 2008?)

	* ccedilla (U+00E7): X=304.0,Y=-1.0 (should be at baseline 0?)

	* ugrave (U+00F9): X=174.0,Y=-1.5 (should be at baseline 0?)

	* uacute (U+00FA): X=174.0,Y=-1.5 (should be at baseline 0?)

	* ucircumflex (U+00FB): X=174.0,Y=-1.5 (should be at baseline 0?)

	* udieresis (U+00FC): X=174.0,Y=-1.5 (should be at baseline 0?)

	* yacute (U+00FD): X=194.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=194.0,Y=-1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=1129.0,Y=2575.0 (should be at ascender 2576?)

	* Dcaron (U+010E): X=1209.0,Y=2575.0 (should be at ascender 2576?)

	* Ecaron (U+011A): X=1112.0,Y=2575.0 (should be at ascender 2576?)

	* gbreve (U+011F): X=495.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=495.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=495.0,Y=1.5 (should be at baseline 0?)

	* Ncaron (U+0147): X=1239.0,Y=2575.0 (should be at ascender 2576?)

	* Eng (U+014A): X=199.0,Y=2.0 (should be at baseline 0?)

	* Eng (U+014A): X=199.0,Y=2.0 (should be at baseline 0?)

	* Rcaron (U+0158): X=1209.0,Y=2575.0 (should be at ascender 2576?)

	* scedilla (U+015F): X=244.0,Y=-1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=1123.0,Y=2575.0 (should be at ascender 2576?)

	* Tcaron (U+0164): X=1146.0,Y=2575.0 (should be at ascender 2576?)

	* umacron (U+016B): X=174.0,Y=-1.5 (should be at baseline 0?)

	* ubreve (U+016D): X=174.0,Y=-1.5 (should be at baseline 0?)

	* uring (U+016F): X=174.0,Y=-1.5 (should be at baseline 0?)

	* uhungarumlaut (U+0171): X=174.0,Y=-1.5 (should be at baseline 0?)

	* Uogonek (U+0172): X=943.5,Y=-1.5 (should be at baseline 0?)

	* uogonek (U+0173): X=174.0,Y=-1.5 (should be at baseline 0?)

	* ycircumflex (U+0177): X=194.0,Y=-1.0 (should be at baseline 0?)

	* Zcaron (U+017D): X=1240.0,Y=2575.0 (should be at ascender 2576?)

	* ygrave (U+1EF3): X=194.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* numbersign (U+0023) contains a short segment B<<1249.0,133.0>-<1243.0,106.0>-<1228.0,75.0>>

	* numbersign (U+0023) contains a short segment B<<687.0,133.0>-<681.0,106.0>-<665.5,75.0>>

	* five (U+0035) contains a short segment B<<449.5,937.0>-<428.0,931.0>-<402.0,931.0>>

	* five (U+0035) contains a short segment B<<646.0,1271.0>-<657.0,1272.0>-<668.5,1272.0>>

	* five (U+0035) contains a short segment B<<668.5,1272.0>-<680.0,1272.0>-<691.0,1272.0>>

	* at (U+0040) contains a short segment B<<1266.0,1180.0>-<1287.0,1224.0>-<1323.0,1242.5>>

	* at (U+0040) contains a short segment B<<1398.0,554.0>-<1392.0,531.0>-<1387.5,499.5>>

	* at (U+0040) contains a short segment B<<1387.5,499.5>-<1383.0,468.0>-<1388.5,444.5>>

	* at (U+0040) contains a short segment B<<1388.5,444.5>-<1394.0,421.0>-<1416.0,421.0>>

	* D (U+0044) contains a short segment L<<419.0,300.0>--<423.0,300.0>>

	* M (U+004D) contains a short segment B<<1811.0,1962.5>-<1844.0,1994.0>-<1875.0,2001.0>>

	* M (U+004D) contains a short segment B<<1875.0,2001.0>-<1906.0,2008.0>-<1943.0,2008.0>>

	* d (U+0064) contains a short segment B<<938.5,292.0>-<939.0,268.0>-<952.0,268.0>>

	* f (U+0066) contains a short segment B<<860.0,1639.0>-<856.0,1650.0>-<848.0,1665.0>>

	* f (U+0066) contains a short segment B<<848.0,1665.0>-<840.0,1680.0>-<826.0,1680.0>>

	* j (U+006A) contains a short segment B<<-161.0,-596.0>-<-158.0,-611.0>-<-148.0,-611.0>>

	* j (U+006A) contains a short segment B<<-148.0,-611.0>-<-142.0,-611.0>-<-134.0,-595.5>>

	* l (U+006C) contains a short segment B<<403.5,292.0>-<403.0,268.0>-<412.0,268.0>>

	* q (U+0071) contains a short segment B<<707.0,-634.5>-<707.0,-658.0>-<720.0,-658.0>>

	* y (U+0079) contains a short segment B<<414.0,292.0>-<420.0,266.0>-<441.0,266.0>>

	* yen (U+00A5) contains a short segment L<<394.0,375.0>--<369.0,375.0>>

	* Eth (U+00D0) contains a short segment L<<419.0,300.0>--<423.0,300.0>>

	* yacute (U+00FD) contains a short segment B<<414.0,292.0>-<420.0,266.0>-<441.0,266.0>>

	* ydieresis (U+00FF) contains a short segment B<<414.0,292.0>-<420.0,266.0>-<441.0,266.0>>

	* Dcaron (U+010E) contains a short segment L<<419.0,300.0>--<423.0,300.0>>

	* dcaron (U+010F) contains a short segment B<<938.5,292.0>-<939.0,268.0>-<952.0,268.0>>

	* Dcroat (U+0110) contains a short segment L<<419.0,300.0>--<423.0,300.0>>

	* dcroat (U+0111) contains a short segment B<<938.5,292.0>-<939.0,268.0>-<952.0,268.0>>

	* lacute (U+013A) contains a short segment B<<403.5,292.0>-<403.0,268.0>-<412.0,268.0>>

	* uni013C (U+013C) contains a short segment B<<403.5,292.0>-<403.0,268.0>-<412.0,268.0>>

	* lcaron (U+013E) contains a short segment B<<403.5,292.0>-<403.0,268.0>-<412.0,268.0>>

	* lslash (U+0142) contains a short segment B<<403.5,292.0>-<403.0,268.0>-<412.0,268.0>>

	* eng (U+014B) contains a short segment B<<324.5,-504.0>-<360.0,-504.0>-<375.0,-503.0>>

	* eng (U+014B) contains a short segment B<<375.0,-503.0>-<390.0,-502.0>-<408.0,-501.0>>

	* eng (U+014B) contains a short segment B<<914.0,833.0>-<911.0,863.0>-<888.0,863.0>>

	* ycircumflex (U+0177) contains a short segment B<<414.0,292.0>-<420.0,266.0>-<441.0,266.0>>

	* uni0237 (U+0237) contains a short segment B<<-161.0,-596.0>-<-158.0,-611.0>-<-148.0,-611.0>>

	* uni0237 (U+0237) contains a short segment B<<-148.0,-611.0>-<-142.0,-611.0>-<-134.0,-595.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<690.0,0.0>-<668.0,1.0>-<633.5,11.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<633.5,11.5>-<599.0,22.0>-<573.5,51.5>>

	* ygrave (U+1EF3) contains a short segment B<<414.0,292.0>-<420.0,266.0>-<441.0,266.0>>

	* Euro (U+20AC) contains a short segment B<<1484.0,624.0>-<1484.0,608.0>-<1470.0,568.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* A (U+0041): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Aacute (U+00C1): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Aacute (U+00C1): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Abreve (U+0102): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Abreve (U+0102): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Acircumflex (U+00C2): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Acircumflex (U+00C2): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Adieresis (U+00C4): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Adieresis (U+00C4): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Agrave (U+00C0): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Agrave (U+00C0): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Amacron (U+0100): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Amacron (U+0100): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Aogonek (U+0104): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Aogonek (U+0104): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Aring (U+00C5): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Aring (U+00C5): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>>

	* Atilde (U+00C3): L<<1040.0,1082.0>--<1049.0,1273.0>> -> L<<1049.0,1273.0>--<1082.0,1605.0>>

	* Atilde (U+00C3): L<<1082.0,1605.0>--<934.0,1275.0>> -> L<<934.0,1275.0>--<833.0,1082.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] TASSchoolHand-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "TASSchoolHand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 965, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, malayalam, math, coptic, canadian-aboriginal, syriac, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _part.c.out.fin

	- _part.e.cv05.alt

	- e.init

	- grave.001

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tilde.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 842 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 759:
greater, less

Width = 844:
lessequal, plusminus, multiply

Width = 843:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=486.0,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=-7.0,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=-7.0,Y=-1.0 (should be at baseline 0?)

	* four (U+0034): X=806.0,Y=2007.0 (should be at cap-height 2008?)

	* Q (U+0051): X=1214.0,Y=2.0 (should be at baseline 0?)

	* X (U+0058): X=1599.0,Y=2007.5 (should be at cap-height 2008?)

	* X (U+0058): X=-15.0,Y=1.0 (should be at baseline 0?)

	* Y (U+0059): X=1523.5,Y=2006.5 (should be at cap-height 2008?)

	* Y (U+0059): X=313.0,Y=0.5 (should be at baseline 0?)

	* p (U+0070): X=-74.0,Y=-903.5 (should be at descender -903?)

	* braceleft (U+007B): X=129.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=801.0,Y=2009.0 (should be at cap-height 2008?)

	* section (U+00A7): X=1063.0,Y=2009.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=1389.0,Y=2010.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=574.0,Y=2010.0 (should be at cap-height 2008?)

	* cedilla (U+00B8): X=-113.0,Y=-2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=506.0,Y=-2.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=1523.5,Y=2006.5 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=313.0,Y=0.5 (should be at baseline 0?)

	* germandbls (U+00DF): X=98.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=98.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=239.0,Y=-2.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=865.5,Y=2578.0 (should be at ascender 2576?)

	* Dcaron (U+010E): X=943.5,Y=2578.0 (should be at ascender 2576?)

	* Ecaron (U+011A): X=814.5,Y=2578.0 (should be at ascender 2576?)

	* Ncaron (U+0147): X=969.5,Y=2578.0 (should be at ascender 2576?)

	* Rcaron (U+0158): X=937.5,Y=2578.0 (should be at ascender 2576?)

	* scedilla (U+015F): X=250.0,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=876.5,Y=2578.0 (should be at ascender 2576?)

	* Tcaron (U+0164): X=716.5,Y=2578.0 (should be at ascender 2576?)

	* Ycircumflex (U+0176): X=1523.5,Y=2006.5 (should be at cap-height 2008?)

	* Ycircumflex (U+0176): X=313.0,Y=0.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=1523.5,Y=2006.5 (should be at cap-height 2008?)

	* Ydieresis (U+0178): X=313.0,Y=0.5 (should be at baseline 0?)

	* Zcaron (U+017D): X=972.5,Y=2578.0 (should be at ascender 2576?)

	* ogonek (U+02DB): X=182.0,Y=-2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=-113.0,Y=-2.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=182.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=545.0,Y=1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=1523.5,Y=2006.5 (should be at cap-height 2008?)

	* Ygrave (U+1EF2): X=313.0,Y=0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* A (U+0041): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* AE (U+00C6): L<<933.0,1839.0>--<825.0,1579.0>> -> L<<825.0,1579.0>--<606.0,1139.0>>

	* AE (U+00C6): L<<975.0,1139.0>--<942.0,1560.0>> -> L<<942.0,1560.0>--<933.0,1839.0>>

	* Aacute (U+00C1): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Aacute (U+00C1): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Abreve (U+0102): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Abreve (U+0102): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Acircumflex (U+00C2): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Acircumflex (U+00C2): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Adieresis (U+00C4): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Adieresis (U+00C4): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Agrave (U+00C0): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Agrave (U+00C0): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Amacron (U+0100): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Amacron (U+0100): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Aogonek (U+0104): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Aogonek (U+0104): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Aring (U+00C5): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Aring (U+00C5): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* Atilde (U+00C3): L<<1098.0,1135.0>--<1094.0,1477.0>> -> L<<1094.0,1477.0>--<1100.0,1788.0>>

	* Atilde (U+00C3): L<<1100.0,1788.0>--<930.0,1487.0>> -> L<<930.0,1487.0>--<713.0,1135.0>>

	* oslash (U+00F8): L<<248.0,164.0>--<427.0,529.0>> -> L<<427.0,529.0>--<638.0,974.0>>

	* oslash (U+00F8): L<<733.0,900.0>--<523.0,475.0>> -> L<<523.0,475.0>--<347.0,104.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<1091.0,1167.0>-<936.0,1085.0>-<658.0,1075.0>>/B<<658.0,1075.0>-<970.0,1011.0>-<1108.5,851.0>> = 13.65228643401414

	* U (U+0055): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Uacute (U+00DA): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Ubreve (U+016C): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Ucircumflex (U+00DB): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Udieresis (U+00DC): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Ugrave (U+00D9): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Uhungarumlaut (U+0170): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Umacron (U+016A): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Uogonek (U+0172): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* Uring (U+016E): L<<1064.0,69.0>--<1211.0,660.0>>/B<<1211.0,660.0>-<1039.0,336.0>-<853.5,158.5>> = 13.994442442841612

	* m (U+006D): B<<974.0,881.0>-<977.0,779.0>-<944.0,649.0>>/B<<944.0,649.0>-<1057.0,858.0>-<1174.5,980.0>> = 14.155292439281338

	* n (U+006E): L<<409.0,1015.0>--<307.0,604.0>>/B<<307.0,604.0>-<378.0,742.0>-<474.0,855.0>> = 13.287694797481715

	* nacute (U+0144): L<<409.0,1015.0>--<307.0,604.0>>/B<<307.0,604.0>-<378.0,742.0>-<474.0,855.0>> = 13.287694797481715

	* ncaron (U+0148): L<<409.0,1015.0>--<307.0,604.0>>/B<<307.0,604.0>-<378.0,742.0>-<474.0,855.0>> = 13.287694797481715

	* ntilde (U+00F1): L<<409.0,1015.0>--<307.0,604.0>>/B<<307.0,604.0>-<378.0,742.0>-<474.0,855.0>> = 13.287694797481715

	* r (U+0072): L<<409.0,1015.0>--<313.0,630.0>>/B<<313.0,630.0>-<386.0,769.0>-<474.5,875.0>> = 13.706328997952227

	* racute (U+0155): L<<409.0,1015.0>--<313.0,630.0>>/B<<313.0,630.0>-<386.0,769.0>-<474.5,875.0>> = 13.706328997952227

	* rcaron (U+0159): L<<409.0,1015.0>--<313.0,630.0>>/B<<313.0,630.0>-<386.0,769.0>-<474.5,875.0>> = 13.706328997952227

	* u (U+0075): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* uacute (U+00FA): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* ubreve (U+016D): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* ucircumflex (U+00FB): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* udieresis (U+00FC): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* ugrave (U+00F9): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* uhungarumlaut (U+0171): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* umacron (U+016B): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* uni0146 (U+0146): L<<409.0,1015.0>--<307.0,604.0>>/B<<307.0,604.0>-<378.0,742.0>-<474.0,855.0>> = 13.287694797481715

	* uni0157 (U+0157): L<<409.0,1015.0>--<313.0,630.0>>/B<<313.0,630.0>-<386.0,769.0>-<474.5,875.0>> = 13.706328997952227

	* uogonek (U+0173): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* uring (U+016F): L<<700.0,90.0>--<795.0,469.0>>/B<<795.0,469.0>-<723.0,330.0>-<635.0,219.0>> = 13.311697824996353

	* y (U+0079): L<<499.0,-631.0>--<764.0,434.0>>/B<<764.0,434.0>-<692.0,298.0>-<607.0,195.5>> = 13.92433779086025

	* yacute (U+00FD): L<<499.0,-631.0>--<764.0,434.0>>/B<<764.0,434.0>-<692.0,298.0>-<607.0,195.5>> = 13.92433779086025

	* ycircumflex (U+0177): L<<499.0,-631.0>--<764.0,434.0>>/B<<764.0,434.0>-<692.0,298.0>-<607.0,195.5>> = 13.92433779086025

	* ydieresis (U+00FF): L<<499.0,-631.0>--<764.0,434.0>>/B<<764.0,434.0>-<692.0,298.0>-<607.0,195.5>> = 13.92433779086025

	* ygrave (U+1EF3): L<<499.0,-631.0>--<764.0,434.0>>/B<<764.0,434.0>-<692.0,298.0>-<607.0,195.5>> = 13.92433779086025 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[21] TASSchoolHand-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'SemiBold'. Expected OS/2 usWeightClass is 600, got 620. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "TASSchoolHand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 965, but got 903 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, malayalam, math, coptic, canadian-aboriginal, syriac, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'TASSchoolHand SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _part.c.out.fin

	- _part.e.cv05.alt

	- e.init

	- grave.001

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- tilde.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 955 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 953:
plus, minus, divide

Width = 861:
less

Width = 862:
greater

Width = 980:
plusminus

Width = 925:
multiply

Width = 930:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* X (U+0058): X=1647.0,Y=2007.5 (should be at cap-height 2008?)

	* Y (U+0059): X=508.5,Y=-2.0 (should be at baseline 0?)

	* h (U+0068): X=985.0,Y=1083.0 (should be at x-height 1082?)

	* m (U+006D): X=1512.0,Y=1082.5 (should be at x-height 1082?)

	* n (U+006E): X=986.5,Y=1083.5 (should be at x-height 1082?)

	* u (U+0075): X=172.5,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=182.0,Y=2.0 (should be at baseline 0?)

	* y (U+0079): X=1013.0,Y=1081.0 (should be at x-height 1082?)

	* braceright (U+007D): X=258.5,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=788.0,Y=2006.0 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=508.5,Y=-2.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=1119.0,Y=2007.0 (should be at cap-height 2008?)

	* ccedilla (U+00E7): X=287.0,Y=-1.0 (should be at baseline 0?)

	* ugrave (U+00F9): X=172.5,Y=1.0 (should be at baseline 0?)

	* uacute (U+00FA): X=172.5,Y=1.0 (should be at baseline 0?)

	* ucircumflex (U+00FB): X=172.5,Y=1.0 (should be at baseline 0?)

	* udieresis (U+00FC): X=172.5,Y=1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=182.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=182.0,Y=2.0 (should be at baseline 0?)

	* Eng (U+014A): X=172.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=172.0,Y=1.0 (should be at baseline 0?)

	* eng (U+014B): X=178.0,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=246.0,Y=-1.0 (should be at baseline 0?)

	* umacron (U+016B): X=172.5,Y=1.0 (should be at baseline 0?)

	* ubreve (U+016D): X=172.5,Y=1.0 (should be at baseline 0?)

	* uring (U+016F): X=172.5,Y=1.0 (should be at baseline 0?)

	* uhungarumlaut (U+0171): X=172.5,Y=1.0 (should be at baseline 0?)

	* uogonek (U+0173): X=172.5,Y=1.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=508.5,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=182.0,Y=2.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=508.5,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=873.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=656.0,Y=2006.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1810.0,Y=2006.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=873.0,Y=-2.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=508.5,Y=-2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=182.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* numbersign (U+0023) contains a short segment B<<1199.0,114.0>-<1193.0,89.0>-<1180.0,63.0>>

	* numbersign (U+0023) contains a short segment B<<1180.0,63.0>-<1167.0,37.0>-<1138.5,18.5>>

	* numbersign (U+0023) contains a short segment B<<630.0,114.0>-<624.0,89.0>-<611.0,63.0>>

	* numbersign (U+0023) contains a short segment B<<611.0,63.0>-<598.0,37.0>-<569.0,18.5>>

	* three (U+0033) contains a short segment B<<83.0,642.0>-<108.0,646.0>-<127.0,646.0>>

	* five (U+0035) contains a short segment B<<421.5,963.5>-<401.0,958.0>-<377.0,958.0>>

	* five (U+0035) contains a short segment B<<377.0,958.0>-<356.0,958.0>-<328.0,964.0>>

	* at (U+0040) contains a short segment B<<1335.0,560.0>-<1324.0,520.0>-<1320.0,479.5>>

	* at (U+0040) contains a short segment B<<1320.0,479.5>-<1316.0,439.0>-<1323.0,411.5>>

	* at (U+0040) contains a short segment B<<1323.0,411.5>-<1330.0,384.0>-<1355.0,384.0>>

	* G (U+0047) contains a short segment B<<1287.0,1087.0>-<1309.0,1095.0>-<1337.0,1095.0>>

	* H (U+0048) contains a short segment B<<321.0,113.0>-<315.0,89.0>-<302.0,63.0>>

	* M (U+004D) contains a short segment B<<664.0,2008.0>-<708.0,2008.0>-<743.0,2000.5>>

	* M (U+004D) contains a short segment B<<743.0,2000.5>-<778.0,1993.0>-<800.5,1963.5>>

	* M (U+004D) contains a short segment B<<1839.0,1967.5>-<1867.0,1994.0>-<1894.5,2001.0>>

	* M (U+004D) contains a short segment B<<1894.5,2001.0>-<1922.0,2008.0>-<1956.0,2008.0>>

	* M (U+004D) contains a short segment B<<1685.0,102.0>-<1676.0,66.0>-<1650.0,33.0>>

	* M (U+004D) contains a short segment B<<1466.5,27.0>-<1438.0,54.0>-<1430.0,91.5>>

	* M (U+004D) contains a short segment B<<1430.0,91.5>-<1422.0,129.0>-<1430.0,161.0>>

	* M (U+004D) contains a short segment B<<931.0,20.5>-<895.0,0.0>-<856.0,0.0>>

	* Z (U+005A) contains a short segment B<<63.0,16.0>-<31.0,32.0>-<21.0,46.0>>

	* Z (U+005A) contains a short segment B<<1680.0,1978.0>-<1697.0,1962.0>-<1710.5,1935.5>>

	* j (U+006A) contains a short segment B<<-203.0,-654.5>-<-193.0,-666.0>-<-180.0,-666.0>>

	* Gbreve (U+011E) contains a short segment B<<1287.0,1087.0>-<1309.0,1095.0>-<1337.0,1095.0>>

	* Gdotaccent (U+0120) contains a short segment B<<1287.0,1087.0>-<1309.0,1095.0>-<1337.0,1095.0>>

	* uni0122 (U+0122) contains a short segment B<<1287.0,1087.0>-<1309.0,1095.0>-<1337.0,1095.0>>

	* Lslash (U+0141) contains a short segment L<<152.0,527.0>--<142.0,522.0>>

	* eng (U+014B) contains a short segment B<<363.5,-542.0>-<383.0,-541.0>-<405.0,-538.0>>

	* Zacute (U+0179) contains a short segment B<<63.0,16.0>-<31.0,32.0>-<21.0,46.0>>

	* Zacute (U+0179) contains a short segment B<<1680.0,1978.0>-<1697.0,1962.0>-<1710.5,1935.5>>

	* Zdotaccent (U+017B) contains a short segment B<<63.0,16.0>-<31.0,32.0>-<21.0,46.0>>

	* Zdotaccent (U+017B) contains a short segment B<<1680.0,1978.0>-<1697.0,1962.0>-<1710.5,1935.5>>

	* Zcaron (U+017D) contains a short segment B<<63.0,16.0>-<31.0,32.0>-<21.0,46.0>>

	* Zcaron (U+017D) contains a short segment B<<1680.0,1978.0>-<1697.0,1962.0>-<1710.5,1935.5>>

	* uni0237 (U+0237) contains a short segment B<<-203.0,-654.5>-<-193.0,-666.0>-<-180.0,-666.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<651.0,0.0>-<632.0,1.0>-<603.0,10.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<603.0,10.5>-<574.0,20.0>-<553.0,44.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<1810.0,2006.0>-<1852.0,2006.0>-<1880.5,1988.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1880.5,1988.0>-<1909.0,1970.0>-<1923.0,1939.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1923.0,1939.0>-<1936.0,1911.0>-<1931.0,1873.5>>

	* Euro (U+20AC) contains a short segment B<<1439.0,611.0>-<1439.0,596.0>-<1425.0,559.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* A (U+0041): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* AE (U+00C6): L<<962.0,1673.0>--<868.0,1437.0>> -> L<<868.0,1437.0>--<726.0,1155.0>>

	* AE (U+00C6): L<<981.0,1155.0>--<958.0,1430.0>> -> L<<958.0,1430.0>--<962.0,1673.0>>

	* Aacute (U+00C1): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Aacute (U+00C1): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Abreve (U+0102): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Abreve (U+0102): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Acircumflex (U+00C2): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Acircumflex (U+00C2): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Adieresis (U+00C4): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Adieresis (U+00C4): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Agrave (U+00C0): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Agrave (U+00C0): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Amacron (U+0100): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Amacron (U+0100): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Aogonek (U+0104): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Aogonek (U+0104): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Aring (U+00C5): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Aring (U+00C5): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* Atilde (U+00C3): L<<1055.0,1096.0>--<1061.0,1327.0>> -> L<<1061.0,1327.0>--<1087.0,1654.0>>

	* Atilde (U+00C3): L<<1087.0,1654.0>--<933.0,1332.0>> -> L<<933.0,1332.0>--<801.0,1096.0>>

	* oslash (U+00F8): L<<338.0,296.0>--<472.0,539.0>> -> L<<472.0,539.0>--<619.0,866.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 22 | 45 | 486 | 21 | 359 | 0 |
| 1% | 2% | 5% | 51% | 2% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
