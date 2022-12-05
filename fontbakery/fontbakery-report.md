## Fontbakery report

Fontbakery version: 0.8.7

<details><summary><b>[22] BIZUDPMincho-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage.</summary><div>
* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)

* 🔥 **FAIL** Missing required codepoints:

	- 0x2215 (DIVISION SLASH)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries.</summary><div>
* [com.google.fonts/check/name/familyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname)

* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUDP Mincho Black" but got "BIZ UDPMincho Black". [code: mismatch]
* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUDP Mincho Black" but got "BIZ UDP明朝 Black". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries.</summary><div>
* [com.google.fonts/check/name/fullfontname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname)

* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUDP Mincho Black"
But got:  "BIZ UDPMincho Black" [code: bad-entry]
* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUDP Mincho Black"
But got:  "BIZ UDP明朝 Black" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries.</summary><div>
* [com.google.fonts/check/name/typographicfamilyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname)

* 🔥 **FAIL** [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)]
Expected: "BIZUDP Mincho"
But got:  "BIZ UDPMincho". [code: non-ribbi-bad-value]
* 🔥 **FAIL** [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)]
Expected: "BIZUDP Mincho"
But got:  "BIZ UDP明朝". [code: non-ribbi-bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions?</summary><div>
* [com.google.fonts/check/smart_dropout](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout)

* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has correct post table version?</summary><div>
* [com.google.fonts/check/post_table_version](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/post.html#com.google.fonts/check/post_table_version)

* 🔥 **FAIL** Post table should be version 2 instead of 3.0. [code: post-table-version]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large.</summary><div>
* [com.google.fonts/check/file_size](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size)

* ⚠ **WARN** Font file is 6.8Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering?</summary><div>
* [com.google.fonts/check/gasp](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp)

* ⚠ **WARN** The gasp table has a range of 7 that may be unneccessary. [code: non-ffff-range]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary><div>
* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)

* ⚠ **WARN** GDEF table is missing, but it is mandatory to declare it on fonts that provide ligature glyphs because the caret (text cursor) positioning for each ligature must be provided in this table. [code: GDEF-missing]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- glyph01077
	- glyph00962
	- glyph01082
	- glyph12929
	- glyph00826
	- glyph00915
	- glyph00922
	- glyph00026
	- glyph00034
	- glyph00533 
	- And 1113 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: registered	Contours detected: 5	Expected: 3 or 4
	- Glyph name: uni0403	Contours detected: 1	Expected: 2
	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: registered	Contours detected: 5	Expected: 3 or 4
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 
	- And Glyph name: uni0403	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features?</summary><div>
* [com.google.fonts/check/cjk_chws_feature](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature)

* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table?</summary><div>
* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)

* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value</summary><div>
* [com.google.fonts/check/gpos_kerning_info](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info)

* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* u20DE1 (U+20DE1): B<<1757.0,243.5>-<1707.0,260.0>-<1659.0,279.0>>/B<<1659.0,279.0>-<1722.0,237.0>-<1748.0,211.5>> = 12.094757077012089
	* u20F5F (U+20F5F): B<<803.0,1276.0>-<773.0,1323.0>-<733.0,1360.0>>/B<<733.0,1360.0>-<746.0,1340.0>-<743.5,1326.0>> = 14.207307052234608
	* u21201 (U+21201): L<<1642.0,1485.0>--<890.0,1485.0>>/B<<890.0,1485.0>-<1006.0,1458.0>-<1067.0,1434.5>> = 13.102789941262442
	* u21255 (U+21255): B<<760.0,1284.5>-<784.0,1247.0>-<806.0,1205.0>>/L<<806.0,1205.0>--<786.0,1278.0>> = 12.324465288873863
	* u213C4 (U+213C4): L<<1999.0,473.0>--<1011.0,473.0>>/B<<1011.0,473.0>-<1131.0,459.0>-<1179.0,443.0>> = 6.654425046006582
	* u21DA1 (U+21DA1): L<<872.0,391.0>--<848.0,485.0>>/L<<848.0,485.0>--<848.0,123.0>> = 14.32271997820355
	* u21F1E (U+21F1E): L<<547.0,1223.0>--<520.0,1223.0>>/B<<520.0,1223.0>-<638.0,1215.0>-<690.5,1201.5>> = 3.8785245028476374
	* u2231E (U+2231E): B<<764.5,896.0>-<785.0,867.0>-<786.0,847.0>>/L<<786.0,847.0>--<786.0,1618.0>> = 2.862405226111651
	* u2231E (U+2231E): L<<786.0,213.0>--<786.0,843.0>>/B<<786.0,843.0>-<785.0,822.0>-<762.0,805.0>> = 2.726310993906212
	* u22AB8 (U+22AB8): B<<860.5,729.5>-<1132.0,756.0>-<1358.0,799.0>>/B<<1358.0,799.0>-<1339.0,800.0>-<1321.0,801.0>> = 13.785435152404041 and 1504 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * u231C3 (U+231C3): L<<1059.0,361.0>--<1411.0,364.0>>
 * u231C3 (U+231C3): L<<1059.0,58.0>--<1411.0,61.0>>
 * u231C3 (U+231C3): L<<1411.0,-88.0>--<1059.0,-91.0>>
 * u231C3 (U+231C3): L<<1411.0,223.0>--<1059.0,220.0>>
 * u2355A (U+2355A): L<<1033.0,932.0>--<1276.0,931.0>>
 * u2355A (U+2355A): L<<1525.0,931.0>--<1786.0,930.0>>
 * u24E0E (U+24E0E): L<<1270.0,1499.0>--<1675.0,1501.0>>
 * u24E0E (U+24E0E): L<<1968.0,1354.0>--<555.0,1348.0>>
 * u24E0E (U+24E0E): L<<574.0,1496.0>--<1004.0,1498.0>>
 * u24E37 (U+24E37): L<<1270.0,1520.0>--<1675.0,1522.0>> and 182 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[22] BIZUDMincho-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage.</summary><div>
* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)

* 🔥 **FAIL** Missing required codepoints:

	- 0x2215 (DIVISION SLASH)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries.</summary><div>
* [com.google.fonts/check/name/familyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname)

* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUD Mincho Black" but got "BIZ UDMincho Black". [code: mismatch]
* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUD Mincho Black" but got "BIZ UD明朝 Black". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries.</summary><div>
* [com.google.fonts/check/name/fullfontname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname)

* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUD Mincho Black"
But got:  "BIZ UDMincho Black" [code: bad-entry]
* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUD Mincho Black"
But got:  "BIZ UD明朝 Black" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries.</summary><div>
* [com.google.fonts/check/name/typographicfamilyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname)

* 🔥 **FAIL** [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)]
Expected: "BIZUD Mincho"
But got:  "BIZ UDMincho". [code: non-ribbi-bad-value]
* 🔥 **FAIL** [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)]
Expected: "BIZUD Mincho"
But got:  "BIZ UD明朝". [code: non-ribbi-bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions?</summary><div>
* [com.google.fonts/check/smart_dropout](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout)

* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has correct post table version?</summary><div>
* [com.google.fonts/check/post_table_version](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/post.html#com.google.fonts/check/post_table_version)

* 🔥 **FAIL** Post table should be version 2 instead of 3.0. [code: post-table-version]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Please set PANOSE Proportion to 9 (monospaced) [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 1482 glyphs (10.64%) have a different width. You should check the widths of: ['space', 'exclam', 'quotedbl', 'numbersign', 'dollar', 'percent', 'ampersand', 'quotesingle', 'parenleft', 'parenright', 'asterisk', 'plus', 'comma', 'hyphen', 'period', 'slash', 'zero', 'one', 'two', 'three', 'four', 'five', 'six', 'seven', 'eight', 'nine', 'colon', 'semicolon', 'less', 'equal', 'greater', 'question', 'at', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z', 'bracketleft', 'backslash', 'bracketright', 'asciicircum', 'underscore', 'grave', 'a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'braceleft', 'bar', 'braceright', 'asciitilde', 'notsubset', 'uni2285', 'uni228A', 'uni228B', 'notelement', 'emptyset', 'uni2305', 'uni2306', 'circleplus', 'uni2296', 'circlemultiply', 'uni2226', 'uni2262', 'uni2243', 'congruent', 'approxequal', 'uni2276', 'uni2277', 'arrowboth', 'uni266E', 'musicalnotedbl', 'uni266C', 'uni2669', 'uni25B7', 'uni25B6', 'uni25C1', 'uni25C0', 'uni2197', 'uni2198', 'uni2196', 'uni2199', 'uni21C4', 'uni21E8', 'uni21E6', 'uni21E7', 'uni21E9', 'uni2934', 'uni2935', 'uni25C9', 'openbullet', 'bullet', 'uni2213', 'aleph', 'uni210F', 'uni2113', 'uni2127', 'endash', 'uni29FA', 'uni29FB', 'uni2664', 'spade', 'uni2662', 'diamond', 'uni2661', 'heart', 'uni2667', 'club', 'sigma1', 'uni25B1', 'uni22DA', 'uni22DB', 'onethird', 'twothirds', 'uni2155', 'uni25D0', 'uni25D1', 'uni25D2', 'uni25D3', 'exclamdbl', 'uni2047', 'uni2048', 'uni2049', 'uni1E3E', 'uni1E3F', 'uni01F8', 'uni01F9', 'Euro', 'exclamdown', 'currency', 'brokenbar', 'copyright', 'ordfeminine', 'guillemotleft', 'registered', 'macron', 'uni0304', 'uni00B2', 'uni00B3', 'periodcentered', 'cedilla', 'uni00B9', 'ordmasculine', 'guillemotright', 'onequarter', 'onehalf', 'threequarters', 'questiondown', 'Agrave', 'Aacute', 'Acircumflex', 'Atilde', 'Adieresis', 'Aring', 'AE', 'Ccedilla', 'Egrave', 'Eacute', 'Ecircumflex', 'Edieresis', 'Igrave', 'Iacute', 'Icircumflex', 'Idieresis', 'Eth', 'Ntilde', 'Ograve', 'Oacute', 'Ocircumflex', 'Otilde', 'Odieresis', 'Oslash', 'Ugrave', 'Uacute', 'Ucircumflex', 'Udieresis', 'Yacute', 'Thorn', 'germandbls', 'agrave', 'aacute', 'acircumflex', 'atilde', 'adieresis', 'aring', 'ae', 'ccedilla', 'egrave', 'eacute', 'ecircumflex', 'edieresis', 'igrave', 'iacute', 'icircumflex', 'idieresis', 'eth', 'ntilde', 'ograve', 'oacute', 'ocircumflex', 'otilde', 'odieresis', 'oslash', 'ugrave', 'uacute', 'ucircumflex', 'udieresis', 'yacute', 'thorn', 'ydieresis', 'Amacron', 'Imacron', 'Umacron', 'Emacron', 'Omacron', 'amacron', 'imacron', 'umacron', 'emacron', 'omacron', 'Aogonek', 'breve', 'Lslash', 'Lcaron', 'Sacute', 'Scaron', 'Scedilla', 'Tcaron', 'Zacute', 'Zcaron', 'Zdotaccent', 'aogonek', 'ogonek', 'lslash', 'lcaron', 'sacute', 'caron', 'scaron', 'scedilla', 'tcaron', 'zacute', 'hungarumlaut', 'zcaron', 'zdotaccent', 'Racute', 'Abreve', 'Lacute', 'Cacute', 'Ccaron', 'Eogonek', 'Ecaron', 'Dcaron', 'Nacute', 'Ncaron', 'Ohungarumlaut', 'Rcaron', 'Uring', 'Uhungarumlaut', 'uni0162', 'racute', 'abreve', 'lacute', 'cacute', 'ccaron', 'eogonek', 'ecaron', 'dcaron', 'dcroat', 'nacute', 'ncaron', 'ohungarumlaut', 'rcaron', 'uring', 'uhungarumlaut', 'uni0163', 'dotaccent', 'Ccircumflex', 'Gcircumflex', 'Hcircumflex', 'Jcircumflex', 'Scircumflex', 'Ubreve', 'ccircumflex', 'gcircumflex', 'hcircumflex', 'jcircumflex', 'scircumflex', 'ubreve', 'uni0271', 'uni028B', 'uni027E', 'uni0283', 'uni0292', 'uni026C', 'uni026E', 'uni0279', 'uni0288', 'uni0256', 'uni0273', 'uni027D', 'uni0282', 'uni0290', 'uni027B', 'uni026D', 'uni025F', 'uni0272', 'uni029D', 'uni028E', 'uni0261', 'eng', 'uni0270', 'uni0281', 'hbar', 'uni0295', 'uni0294', 'uni0266', 'uni0298', 'uni01C2', 'uni0253', 'uni0257', 'uni0284', 'uni0260', 'uni0193', 'oe', 'OE', 'uni0268', 'uni0289', 'uni0258', 'uni0275', 'uni0259', 'uni025C', 'uni025E', 'uni0250', 'uni026F', 'uni028A', 'uni0264', 'uni028C', 'uni0254', 'uni0251', 'uni0252', 'uni028D', 'uni0265', 'uni02A2', 'uni02A1', 'uni0255', 'uni0291', 'uni027A', 'uni0267', 'uni025A', 'aeacute', 'uni1F70', 'uni1F71', 'uni1F72', 'uni1F73', 'uni0361', 'uni02C8', 'uni02CC', 'uni02D0', 'uni02D1', 'uni0306', 'uni203F', 'uni030B', 'acutecomb', 'uni030F', 'uni030C', 'uni0302', 'uni02E5', 'uni02E6', 'uni02E7', 'uni02E8', 'uni02E9', 'uni0325', 'uni032C', 'uni0339', 'uni031C', 'uni031F', 'uni0320', 'uni0308', 'uni033D', 'uni0329', 'uni032F', 'uni02DE', 'uni0324', 'uni0330', 'uni033C', 'uni0334', 'uni031D', 'uni031E', 'uni0318', 'uni0319', 'uni032A', 'uni033A', 'uni033B', 'tilde', 'uni031A', 'uni2042', 'uni00A0', 'glyph01248', 'glyph01249', 'glyph01250', 'glyph01251', 'uni00AD', 'glyph01253', 'minus', 'glyph01255', 'glyph01256', 'glyph01257', 'glyph01258', 'glyph01259', 'glyph01260', 'glyph01261', 'glyph01263', 'glyph01264', 'glyph01265', 'glyph01266', 'glyph01267', 'glyph01268', 'glyph01269', 'glyph01270', 'glyph01271', 'glyph01272', 'glyph01273', 'glyph01274', 'glyph01275', 'glyph01276', 'glyph01277', 'glyph01278', 'glyph01279', 'glyph01280', 'glyph01281', 'glyph01282', 'glyph01283', 'glyph01284', 'glyph01285', 'glyph01286', 'glyph01287', 'glyph01288', 'glyph01289', 'glyph01290', 'glyph01291', 'glyph01292', 'glyph01293', 'glyph01294', 'glyph01295', 'glyph01296', 'glyph01297', 'glyph01298', 'glyph01299', 'glyph01300', 'glyph01301', 'glyph01302', 'glyph01303', 'glyph01304', 'glyph01305', 'gravecomb', 'glyph01308', 'glyph01309', 'glyph01310', 'glyph01311', 'glyph01312', 'glyph01313', 'glyph01314', 'glyph01315', 'glyph01316', 'glyph01317', 'glyph01319', 'glyph01320', 'glyph01321', 'glyph01322', 'glyph01323', 'glyph01324', 'glyph01325', 'glyph01326', 'glyph01327', 'glyph01328', 'glyph01329', 'glyph01330', 'glyph01331', 'glyph01332', 'glyph01333', 'glyph01334', 'glyph01335', 'glyph01336', 'glyph01337', 'glyph01338', 'glyph01339', 'glyph01340', 'glyph01341', 'glyph01342', 'glyph01343', 'glyph01344', 'glyph01345', 'glyph01346', 'glyph01347', 'glyph01348', 'glyph01349', 'glyph01350', 'glyph01351', 'glyph01352', 'glyph01353', 'glyph01354', 'glyph01355', 'glyph01356', 'glyph01357', 'glyph01358', 'glyph01359', 'glyph01360', 'glyph01361', 'glyph01362', 'glyph01363', 'glyph01364', 'glyph01365', 'glyph01366', 'glyph01367', 'glyph01368', 'glyph01369', 'glyph01370', 'glyph01371', 'glyph01372', 'glyph01373', 'glyph01374', 'glyph01375', 'glyph01376', 'glyph01377', 'glyph01378', 'glyph01379', 'glyph01380', 'glyph01381', 'glyph01382', 'glyph01383', 'glyph01384', 'glyph01385', 'glyph01386', 'glyph01387', 'glyph01388', 'glyph01389', 'glyph01390', 'glyph01392', 'glyph01393', 'glyph01394', 'glyph01395', 'glyph01401', 'glyph01402', 'glyph01403', 'glyph01404', 'glyph01405', 'glyph01406', 'glyph01407', 'glyph01408', 'glyph01409', 'glyph01410', 'glyph01412', 'glyph01413', 'glyph01414', 'glyph01415', 'glyph01416', 'glyph01417', 'glyph01420', 'glyph01421', 'glyph01422', 'glyph01423', 'glyph01424', 'glyph01425', 'glyph01426', 'glyph01427', 'glyph01428', 'glyph01429', 'glyph01430', 'glyph01431', 'glyph01432', 'glyph01436', 'glyph01437', 'glyph01438', 'glyph01439', 'glyph01440', 'glyph01441', 'glyph01442', 'glyph01443', 'glyph01445', 'glyph01446', 'glyph01447', 'glyph01448', 'glyph01449', 'glyph01450', 'glyph01451', 'glyph01452', 'glyph01453', 'glyph01454', 'glyph01455', 'glyph01456', 'glyph01457', 'glyph01458', 'glyph01459', 'glyph01463', 'glyph01464', 'glyph01465', 'glyph01466', 'glyph01469', 'glyph01470', 'glyph01473', 'glyph01474', 'glyph01475', 'glyph01476', 'glyph01477', 'glyph01478', 'glyph01479', 'glyph01480', 'glyph01481', 'glyph01482', 'glyph01483', 'glyph01484', 'glyph01485', 'glyph01486', 'glyph01487', 'glyph01488', 'glyph01489', 'glyph01490', 'glyph01491', 'glyph01492', 'glyph01493', 'glyph01494', 'glyph01495', 'glyph01496', 'glyph01497', 'glyph01498', 'glyph01499', 'glyph01500', 'glyph01501', 'glyph01502', 'glyph01503', 'glyph01504', 'glyph01505', 'glyph01506', 'glyph01507', 'glyph01508', 'glyph01509', 'glyph01510', 'glyph01511', 'glyph01512', 'glyph01513', 'glyph01514', 'glyph01515', 'glyph01516', 'glyph01517', 'glyph01518', 'glyph01519', 'glyph01520', 'glyph01522', 'glyph01523', 'glyph01524', 'glyph01525', 'glyph01526', 'glyph01527', 'glyph01528', 'glyph01529', 'glyph01531', 'glyph01532', 'glyph01533', 'glyph01534', 'glyph01535', 'glyph01536', 'glyph01537', 'glyph01538', 'glyph01539', 'glyph01540', 'glyph01543', 'glyph01544', 'glyph01545', 'glyph01546', 'glyph01547', 'glyph01549', 'glyph01550', 'glyph01551', 'glyph01552', 'glyph01553', 'glyph01554', 'glyph01555', 'glyph01556', 'glyph01557', 'glyph01558', 'glyph01559', 'glyph01560', 'glyph01561', 'glyph01562', 'glyph01564', 'glyph01565', 'glyph01566', 'glyph01567', 'glyph01568', 'glyph01569', 'glyph01570', 'glyph01571', 'glyph01572', 'glyph01573', 'glyph01574', 'glyph01575', 'glyph01576', 'glyph01577', 'glyph01578', 'glyph01579', 'glyph01580', 'glyph01581', 'glyph01582', 'glyph01583', 'glyph01584', 'glyph01585', 'glyph01586', 'glyph01587', 'glyph01588', 'glyph01589', 'glyph01590', 'glyph01591', 'glyph01592', 'glyph01593', 'glyph01594', 'glyph01595', 'glyph01596', 'glyph01597', 'glyph01598', 'glyph01599', 'glyph01600', 'glyph01601', 'glyph01602', 'glyph01603', 'glyph01604', 'glyph01609', 'glyph01610', 'glyph01612', 'glyph01613', 'glyph01615', 'glyph01616', 'glyph01617', 'glyph01618', 'glyph01619', 'glyph01621', 'glyph01622', 'glyph01623', 'glyph01624', 'glyph01625', 'glyph01626', 'glyph01627', 'glyph01628', 'glyph01629', 'glyph01630', 'glyph01631', 'glyph01632', 'glyph01633', 'glyph01635', 'glyph01636', 'glyph01638', 'glyph01639', 'glyph01640', 'glyph01641', 'glyph01642', 'glyph01643', 'glyph01644', 'glyph01645', 'glyph01646', 'glyph01647', 'glyph01648', 'glyph01649', 'glyph01650', 'glyph01651', 'glyph01652', 'glyph01653', 'glyph01654', 'glyph01655', 'glyph01656', 'glyph01658', 'glyph01659', 'glyph01660', 'glyph01661', 'glyph01662', 'glyph01663', 'glyph01664', 'glyph01665', 'glyph01666', 'glyph01667', 'glyph01668', 'glyph01669', 'glyph01670', 'glyph01671', 'glyph01672', 'glyph01673', 'glyph01674', 'glyph01675', 'glyph01676', 'glyph01677', 'glyph01678', 'glyph01679', 'glyph01680', 'glyph01681', 'glyph01682', 'glyph01683', 'glyph01684', 'glyph01685', 'glyph01686', 'glyph01687', 'glyph01688', 'glyph01689', 'glyph01690', 'glyph01691', 'glyph01692', 'glyph01693', 'glyph01694', 'glyph01695', 'glyph01696', 'glyph01697', 'glyph01698', 'glyph01699', 'glyph01700', 'glyph01701', 'glyph01702', 'glyph01703', 'glyph01704', 'glyph01705', 'glyph01706', 'glyph01707', 'glyph01708', 'glyph01709', 'glyph01710', 'glyph01711', 'glyph01712', 'glyph01713', 'glyph01714', 'glyph01715', 'glyph01716', 'glyph01717', 'glyph01718', 'glyph01719', 'glyph01720', 'glyph01721', 'glyph01722', 'glyph01723', 'glyph01724', 'glyph01725', 'glyph01726', 'glyph01727', 'glyph01728', 'glyph01729', 'glyph01730', 'glyph01731', 'glyph01732', 'glyph01733', 'glyph01734', 'glyph01735', 'glyph01736', 'glyph01737', 'glyph01738', 'glyph01739', 'glyph01740', 'glyph01741', 'glyph01742', 'glyph01743', 'glyph01744', 'glyph01745', 'glyph01746', 'glyph01747', 'glyph01748', 'glyph01749', 'glyph01750', 'glyph01751', 'glyph01752', 'glyph01753', 'glyph01754', 'glyph01755', 'glyph01756', 'glyph01757', 'glyph01758', 'glyph01759', 'glyph01760', 'glyph01761', 'glyph01762', 'glyph01763', 'glyph01764', 'glyph01765', 'glyph01766', 'glyph01767', 'glyph01768', 'glyph01769', 'glyph01770', 'glyph01771', 'glyph01772', 'glyph01773', 'glyph01774', 'glyph01775', 'glyph01776', 'glyph01777', 'glyph01778', 'glyph01779', 'glyph01780', 'glyph01781', 'glyph01782', 'glyph01783', 'glyph01784', 'glyph01785', 'glyph01786', 'glyph01787', 'glyph01788', 'glyph01789', 'glyph01790', 'glyph01791', 'glyph01792', 'glyph01793', 'glyph01794', 'glyph01795', 'glyph01796', 'glyph01797', 'glyph01798', 'glyph01799', 'glyph01800', 'glyph01801', 'glyph01802', 'glyph01803', 'glyph01804', 'glyph01805', 'glyph01806', 'glyph01807', 'glyph01808', 'glyph01809', 'glyph01810', 'glyph01811', 'glyph01812', 'glyph01813', 'glyph01814', 'glyph01815', 'glyph01816', 'glyph01817', 'glyph01818', 'glyph01819', 'glyph01820', 'glyph01821', 'glyph01822', 'glyph01823', 'glyph01824', 'glyph01825', 'glyph01826', 'glyph01827', 'glyph01830', 'glyph01831', 'glyph01832', 'glyph01833', 'glyph01834', 'glyph01835', 'glyph01836', 'glyph01837', 'glyph01838', 'glyph01839', 'glyph01840', 'glyph01841', 'glyph01842', 'glyph01843', 'glyph01844', 'glyph01845', 'glyph01846', 'glyph01847', 'glyph01848', 'glyph01849', 'glyph01850', 'glyph01851', 'glyph01852', 'glyph01853', 'glyph01855', 'glyph01856', 'glyph01857', 'glyph01858', 'glyph01859', 'glyph01860', 'glyph01861', 'glyph01862', 'glyph01863', 'glyph01864', 'glyph01865', 'glyph01866', 'glyph01867', 'glyph01868', 'glyph01869', 'glyph01870', 'glyph01871', 'glyph01872', 'glyph01873', 'glyph01874', 'glyph01875', 'glyph01876', 'glyph01877', 'glyph01878', 'glyph01879', 'glyph01880', 'glyph01881', 'glyph01882', 'glyph01883', 'glyph01884', 'glyph01885', 'glyph01886', 'glyph01887', 'glyph01888', 'glyph01889', 'glyph01890', 'glyph01891', 'glyph01892', 'glyph01893', 'glyph01894', 'glyph01895', 'glyph01896', 'glyph01897', 'glyph01898', 'glyph01899', 'glyph12253', 'uni203E', 'glyph12255', 'glyph12256', 'glyph12259', 'cent', 'sterling', 'yen', 'logicalnot', 'emdash', 'glyph12284', 'glyph12285', 'glyph12287', 'glyph12289', 'glyph12292', 'glyph12295', 'glyph12296', 'glyph12298', 'glyph12299', 'glyph12300', 'glyph12301', 'glyph12302', 'glyph12303', 'glyph12304', 'glyph12305', 'glyph12306', 'glyph12307', 'glyph12308', 'glyph12309', 'glyph12310', 'glyph12311', 'glyph12312', 'glyph12313', 'glyph12314', 'glyph12315', 'glyph12316', 'uniFF61', 'uniFF62', 'uniFF63', 'uniFF64', 'uniFF65', 'uniFF66', 'uniFF67', 'uniFF68', 'uniFF69', 'uniFF6A', 'uniFF6B', 'uniFF6C', 'uniFF6D', 'uniFF6E', 'uniFF6F', 'uniFF70', 'uniFF71', 'uniFF72', 'uniFF73', 'uniFF74', 'uniFF75', 'uniFF76', 'uniFF77', 'uniFF78', 'uniFF79', 'uniFF7A', 'uniFF7B', 'uniFF7C', 'uniFF7D', 'uniFF7E', 'uniFF7F', 'uniFF80', 'uniFF81', 'uniFF82', 'uniFF83', 'uniFF84', 'uniFF85', 'uniFF86', 'uniFF87', 'uniFF88', 'uniFF89', 'uniFF8A', 'uniFF8B', 'uniFF8C', 'uniFF8D', 'uniFF8E', 'uniFF8F', 'uniFF90', 'uniFF91', 'uniFF92', 'uniFF93', 'uniFF94', 'uniFF95', 'uniFF96', 'uniFF97', 'uniFF98', 'uniFF99', 'uniFF9A', 'uniFF9B', 'uniFF9C', 'uniFF9D', 'uniFF9E', 'uniFF9F', 'glyph12855', 'glyph12856', 'glyph12857', 'glyph12858', 'glyph12859', 'glyph12860', 'glyph12861', 'glyph12862', 'glyph12863', 'glyph12864', 'glyph12865', 'glyph12866', 'glyph12867', 'glyph12868', 'glyph12869', 'glyph12870', 'glyph12871', 'glyph12874', 'glyph12875', 'glyph12876', 'glyph12877', 'glyph12878', 'glyph12879', 'glyph12880', 'glyph12881', 'glyph12882', 'glyph12883', 'glyph12884', 'glyph12885', 'glyph12886', 'glyph12887', 'glyph12888', 'glyph12889', 'glyph12890', 'glyph12891', 'glyph12892', 'glyph12893', 'glyph12894', 'glyph12895', 'glyph12896', 'glyph12897', 'glyph12898', 'glyph12899', 'glyph12900', 'glyph12901', 'glyph12902', 'glyph12903', 'glyph12904', 'glyph12905', 'glyph12906', 'glyph12907', 'glyph12908', 'glyph12909', 'glyph12910', 'glyph12911', 'glyph12912', 'glyph12913', 'glyph12914', 'glyph12915', 'glyph12916', 'glyph12917', 'glyph12918', 'glyph12919', 'glyph12920', 'glyph12921', 'glyph12922', 'glyph12923', 'glyph12924', 'glyph12925', 'glyph12926', 'glyph12927', 'glyph12928', 'glyph12929', 'glyph12930', 'glyph12931', 'glyph12932', 'glyph12933', 'glyph12934', 'glyph12935', 'glyph12936', 'glyph12937', 'glyph12938', 'glyph12939', 'glyph12940', 'glyph12941', 'glyph12942', 'glyph12943', 'glyph12944', 'glyph12945', 'glyph12946', 'glyph12947', 'glyph12948', 'glyph12949', 'glyph12950', 'glyph12951', 'glyph12952', 'glyph12953', 'glyph12954', 'glyph12955', 'glyph12956', 'glyph12957', 'glyph12958', 'glyph12959', 'glyph12960', 'glyph12961', 'glyph12962', 'glyph12963', 'glyph12964', 'glyph12965', 'glyph12966', 'glyph12967', 'glyph12968', 'glyph12969', 'glyph12970', 'glyph12971', 'glyph12972', 'glyph12973', 'glyph12974', 'glyph12975', 'glyph12976', 'glyph12977', 'glyph12978', 'glyph12979', 'glyph12980', 'glyph12981', 'glyph12982', 'glyph12983', 'glyph12984', 'glyph12985', 'glyph12986', 'glyph12987', 'glyph12988', 'glyph12989', 'glyph12990', 'glyph12991', 'glyph12992', 'glyph12993', 'glyph12994', 'glyph12995', 'glyph12996', 'glyph12997', 'glyph12998', 'glyph12999', 'glyph13000', 'glyph13001', 'glyph13002', 'glyph13003', 'glyph13004', 'glyph13005', 'glyph13006', 'glyph13007', 'glyph13008', 'glyph13009', 'glyph13010', 'glyph13011', 'glyph13012', 'glyph13013', 'glyph13014', 'glyph13015', 'glyph13016', 'glyph13017', 'glyph13018', 'glyph13019', 'glyph13020', 'glyph13021', 'glyph13022', 'glyph13023', 'glyph13024', 'glyph13025', 'glyph13026', 'glyph13027', 'glyph13028', 'glyph13029', 'glyph13030', 'glyph13031', 'glyph13032', 'glyph13033', 'glyph13034', 'glyph13035', 'glyph13036', 'glyph13037', 'glyph13038', 'glyph13039', 'glyph13040', 'glyph13041', 'glyph13042', 'glyph13043', 'glyph13044', 'glyph13045', 'glyph13046', 'glyph13047', 'glyph13048', 'glyph13576', 'glyph13671', 'glyph13672', 'glyph13673', 'glyph13674', 'glyph13675', 'glyph13676', 'glyph13677', 'glyph13678', 'glyph13679', 'glyph13680', 'glyph13681', 'glyph13682', 'glyph13683', 'glyph13684', 'glyph13685', 'glyph13686', 'glyph13687', 'glyph13688', 'glyph13689', 'glyph13690', 'glyph13691', 'glyph13692', 'glyph13693', 'glyph13694', 'glyph13695', 'glyph13696', 'glyph13697', 'glyph13698', 'glyph13699', 'glyph13700', 'glyph13701', 'glyph13703', 'glyph13704', 'glyph13705', 'glyph13706', 'glyph13707', 'glyph13708', 'glyph13709', 'glyph13710', 'glyph13711', 'glyph13713', 'glyph13714', 'glyph13715', 'glyph13716', 'glyph13717', 'glyph13718', 'glyph13719', 'glyph13720', 'glyph13721', 'glyph13722', 'glyph13723', 'glyph13724', 'glyph13725', 'glyph13726', 'glyph13727', 'glyph13728', 'glyph13729', 'glyph13730', 'glyph13731', 'glyph13732', 'glyph13733', 'glyph13734', 'glyph13735', 'glyph13736', 'glyph13737', 'glyph13738', 'glyph13739', 'glyph13740', 'glyph13741', 'glyph13813', 'Cdotaccent', 'Dcroat', 'Ebreve', 'Edotaccent', 'Gbreve', 'uni0122', 'Gdotaccent', 'Hbar', 'IJ', 'Ibreve', 'Idotaccent', 'Iogonek', 'Itilde', 'uni0136', 'uni013B', 'Ldot', 'uni0145', 'Eng', 'Obreve', 'uni0156', 'Tbar', 'Uogonek', 'Utilde', 'Wcircumflex', 'Ycircumflex', 'Ydieresis', 'cdotaccent', 'ebreve', 'edotaccent', 'gbreve', 'uni0123', 'gdotaccent', 'dotlessi', 'ibreve', 'ij', 'iogonek', 'itilde', 'uni0137', 'kgreenlandic', 'uni013C', 'ldot', 'napostrophe', 'uni0146', 'obreve', 'uni0157', 'longs', 'tbar', 'uogonek', 'utilde', 'wcircumflex', 'ycircumflex', 'uniFB01', 'uniFB02', 'uni2074', 'fraction', 'quotesinglbase', 'quotedblbase', 'guilsinglleft', 'guilsinglright', 'florin', 'greaterequal', 'lessequal', 'mu', 'lozenge', 'trademark', 'circumflex', 'ring', 'tonos', 'dieresistonos'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large.</summary><div>
* [com.google.fonts/check/file_size](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size)

* ⚠ **WARN** Font file is 6.8Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering?</summary><div>
* [com.google.fonts/check/gasp](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp)

* ⚠ **WARN** The gasp table has a range of 7 that may be unneccessary. [code: non-ffff-range]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary><div>
* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)

* ⚠ **WARN** GDEF table is missing, but it is mandatory to declare it on fonts that provide ligature glyphs because the caret (text cursor) positioning for each ligature must be provided in this table. [code: GDEF-missing]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- glyph01479
	- glyph13650
	- glyph01290
	- glyph01500
	- glyph01660
	- glyph13308
	- glyph01415
	- glyph01540
	- glyph01591
	- glyph01773 
	- And 1285 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: eng	Contours detected: 2	Expected: 1
	- Glyph name: uni0403	Contours detected: 1	Expected: 2
	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: eng	Contours detected: 2	Expected: 1
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 
	- And Glyph name: uni0403	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features?</summary><div>
* [com.google.fonts/check/cjk_chws_feature](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature)

* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table?</summary><div>
* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)

* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* AE (U+00C6): L<<494.0,672.0>--<494.0,1260.0>>/L<<494.0,1260.0>--<356.0,672.0>> = 13.207928462779101
	* b (U+0062): L<<381.0,1597.0>--<381.0,995.0>>/B<<381.0,995.0>-<393.0,1063.0>-<448.0,1105.0>> = 10.007979801441312
	* m (U+006D): B<<558.0,1035.5>-<572.0,997.0>-<573.0,934.0>>/B<<573.0,934.0>-<585.0,1001.0>-<614.0,1048.5>> = 11.063647029399375
	* p (U+0070): L<<381.0,1147.0>--<381.0,977.0>>/B<<381.0,977.0>-<390.0,1026.0>-<418.0,1064.5>> = 10.40771131249005
	* thorn (U+00FE): L<<381.0,1595.0>--<381.0,977.0>>/B<<381.0,977.0>-<390.0,1026.0>-<418.0,1064.5>> = 10.40771131249005
	* u20DE1 (U+20DE1): B<<1757.0,243.5>-<1707.0,260.0>-<1659.0,279.0>>/B<<1659.0,279.0>-<1722.0,237.0>-<1748.0,211.5>> = 12.094757077012089
	* u20F5F (U+20F5F): B<<803.0,1276.0>-<773.0,1323.0>-<733.0,1360.0>>/B<<733.0,1360.0>-<746.0,1340.0>-<743.5,1326.0>> = 14.207307052234608
	* u21201 (U+21201): L<<1642.0,1485.0>--<890.0,1485.0>>/B<<890.0,1485.0>-<1006.0,1458.0>-<1067.0,1434.5>> = 13.102789941262442
	* u21255 (U+21255): B<<760.0,1284.5>-<784.0,1247.0>-<806.0,1205.0>>/L<<806.0,1205.0>--<786.0,1278.0>> = 12.324465288873863
	* u213C4 (U+213C4): L<<1999.0,473.0>--<1011.0,473.0>>/B<<1011.0,473.0>-<1131.0,459.0>-<1179.0,443.0>> = 6.654425046006582 and 1515 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * u231C3 (U+231C3): L<<1059.0,361.0>--<1411.0,364.0>>
 * u231C3 (U+231C3): L<<1059.0,58.0>--<1411.0,61.0>>
 * u231C3 (U+231C3): L<<1411.0,-88.0>--<1059.0,-91.0>>
 * u231C3 (U+231C3): L<<1411.0,223.0>--<1059.0,220.0>>
 * u2355A (U+2355A): L<<1033.0,932.0>--<1276.0,931.0>>
 * u2355A (U+2355A): L<<1525.0,931.0>--<1786.0,930.0>>
 * u24E0E (U+24E0E): L<<1270.0,1499.0>--<1675.0,1501.0>>
 * u24E0E (U+24E0E): L<<1968.0,1354.0>--<555.0,1348.0>>
 * u24E0E (U+24E0E): L<<574.0,1496.0>--<1004.0,1498.0>>
 * u24E37 (U+24E37): L<<1270.0,1520.0>--<1675.0,1522.0>> and 182 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] BIZUDPMincho-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage.</summary><div>
* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)

* 🔥 **FAIL** Missing required codepoints:

	- 0x2215 (DIVISION SLASH)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries.</summary><div>
* [com.google.fonts/check/name/familyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname)

* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUDP Mincho" but got "BIZ UDPMincho". [code: mismatch]
* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUDP Mincho" but got "BIZ UDP明朝". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries.</summary><div>
* [com.google.fonts/check/name/fullfontname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname)

* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUDP Mincho Regular"
But got:  "BIZ UDPMincho" [code: bad-entry]
* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUDP Mincho Regular"
But got:  "BIZ UDP明朝" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions?</summary><div>
* [com.google.fonts/check/smart_dropout](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout)

* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has correct post table version?</summary><div>
* [com.google.fonts/check/post_table_version](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/post.html#com.google.fonts/check/post_table_version)

* 🔥 **FAIL** Post table should be version 2 instead of 3.0. [code: post-table-version]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large.</summary><div>
* [com.google.fonts/check/file_size](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size)

* ⚠ **WARN** Font file is 5.9Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering?</summary><div>
* [com.google.fonts/check/gasp](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp)

* ⚠ **WARN** The gasp table has a range of 7 that may be unneccessary. [code: non-ffff-range]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary><div>
* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)

* ⚠ **WARN** GDEF table is missing, but it is mandatory to declare it on fonts that provide ligature glyphs because the caret (text cursor) positioning for each ligature must be provided in this table. [code: GDEF-missing]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- glyph01077
	- glyph00962
	- glyph01082
	- glyph12929
	- glyph00826
	- glyph00915
	- glyph00922
	- glyph00026
	- glyph00034
	- glyph00533 
	- And 1113 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: uni0403	Contours detected: 1	Expected: 2
	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 
	- And Glyph name: uni0403	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features?</summary><div>
* [com.google.fonts/check/cjk_chws_feature](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature)

* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table?</summary><div>
* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)

* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value</summary><div>
* [com.google.fonts/check/gpos_kerning_info](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info)

* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* u28BC1 (U+28BC1): L<<801.0,-178.0>--<801.0,739.0>>/B<<801.0,739.0>-<737.0,483.0>-<614.0,236.0>> = 14.036243467926484
	* uni24F7 (U+24F7): B<<1230.0,856.0>-<1172.0,820.0>-<1075.0,809.0>>/B<<1075.0,809.0>-<1186.0,796.0>-<1258.0,748.0>> = 13.149706048395707
	* uni322C (U+322C): B<<1277.0,621.0>-<1154.0,842.0>-<1082.0,1137.0>>/L<<1082.0,1137.0>--<1082.0,49.0>> = 13.71590299066549
	* uni3396 (U+3396): B<<545.0,1088.0>-<588.0,1021.0>-<590.0,936.0>>/B<<590.0,936.0>-<605.0,1008.0>-<632.0,1054.0>> = 13.116176212219232
	* uni3396 (U+3396): L<<287.0,1147.0>--<287.0,958.0>>/B<<287.0,958.0>-<306.0,1052.0>-<361.0,1105.0>> = 11.427101593945128
	* uni339C (U+339C): B<<1507.0,1088.0>-<1550.0,1020.0>-<1552.0,936.0>>/B<<1552.0,936.0>-<1567.0,1008.0>-<1594.0,1054.0>> = 13.132216463623552
	* uni339C (U+339C): B<<524.0,1088.0>-<567.0,1021.0>-<569.0,936.0>>/B<<569.0,936.0>-<584.0,1008.0>-<611.0,1054.0>> = 13.116176212219232
	* uni339C (U+339C): L<<1249.0,1147.0>--<1249.0,958.0>>/B<<1249.0,958.0>-<1268.0,1052.0>-<1323.0,1105.0>> = 11.427101593945128
	* uni339C (U+339C): L<<266.0,1147.0>--<266.0,958.0>>/B<<266.0,958.0>-<285.0,1052.0>-<340.0,1105.0>> = 11.427101593945128
	* uni339F (U+339F): B<<1507.0,1088.0>-<1550.0,1020.0>-<1552.0,936.0>>/B<<1552.0,936.0>-<1567.0,1008.0>-<1594.0,1054.0>> = 13.132216463623552 and 171 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * u2074F (U+2074F): L<<1746.0,1251.0>--<1747.0,1416.0>>
 * u26FF8 (U+26FF8): L<<498.0,8.0>--<785.0,9.0>>
 * u273DB (U+273DB): L<<174.0,15.0>--<301.0,14.0>>
 * u273FE (U+273FE): L<<199.0,0.0>--<348.0,1.0>>
 * uni30BB (U+30BB): L<<748.0,865.0>--<746.0,387.0>>
 * uni30BC (U+30BC): L<<748.0,865.0>--<746.0,387.0>>
 * uni31FE (U+31FE): L<<299.0,340.0>--<298.0,531.0>>
 * uni32DD (U+32DD): L<<842.0,843.0>--<840.0,481.0>>
 * uni4453 (U+4453): L<<713.0,446.0>--<846.0,447.0>>
 * uni4E9F (U+4E9F): L<<984.0,1059.0>--<985.0,1174.0>> and 103 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] BIZUDMincho-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage.</summary><div>
* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)

* 🔥 **FAIL** Missing required codepoints:

	- 0x2215 (DIVISION SLASH)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries.</summary><div>
* [com.google.fonts/check/name/familyname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname)

* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUD Mincho" but got "BIZ UDMincho". [code: mismatch]
* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "BIZUD Mincho" but got "BIZ UD明朝". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries.</summary><div>
* [com.google.fonts/check/name/fullfontname](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname)

* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUD Mincho Regular"
But got:  "BIZ UDMincho" [code: bad-entry]
* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "BIZUD Mincho Regular"
But got:  "BIZ UD明朝" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions?</summary><div>
* [com.google.fonts/check/smart_dropout](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout)

* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has correct post table version?</summary><div>
* [com.google.fonts/check/post_table_version](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/post.html#com.google.fonts/check/post_table_version)

* 🔥 **FAIL** Post table should be version 2 instead of 3.0. [code: post-table-version]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Please set PANOSE Proportion to 9 (monospaced) [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 1520 glyphs (10.91%) have a different width. You should check the widths of: ['space', 'exclam', 'quotedbl', 'numbersign', 'dollar', 'percent', 'ampersand', 'quotesingle', 'parenleft', 'parenright', 'asterisk', 'plus', 'comma', 'hyphen', 'period', 'slash', 'zero', 'one', 'two', 'three', 'four', 'five', 'six', 'seven', 'eight', 'nine', 'colon', 'semicolon', 'less', 'equal', 'greater', 'question', 'at', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z', 'bracketleft', 'backslash', 'bracketright', 'asciicircum', 'underscore', 'grave', 'a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'braceleft', 'bar', 'braceright', 'asciitilde', 'notsubset', 'uni2285', 'uni228A', 'uni228B', 'notelement', 'emptyset', 'uni2305', 'uni2306', 'circleplus', 'uni2296', 'circlemultiply', 'uni2226', 'uni2262', 'uni2243', 'congruent', 'approxequal', 'uni2276', 'uni2277', 'arrowboth', 'uni266E', 'musicalnotedbl', 'uni266C', 'uni2669', 'uni25B7', 'uni25B6', 'uni25C1', 'uni25C0', 'uni2197', 'uni2198', 'uni2196', 'uni2199', 'uni21C4', 'uni21E8', 'uni21E6', 'uni21E7', 'uni21E9', 'uni2934', 'uni2935', 'uni25C9', 'openbullet', 'bullet', 'uni2213', 'aleph', 'uni210F', 'uni2113', 'uni2127', 'endash', 'uni29FA', 'uni29FB', 'uni2664', 'spade', 'uni2662', 'diamond', 'uni2661', 'heart', 'uni2667', 'club', 'sigma1', 'uni25B1', 'uni22DA', 'uni22DB', 'onethird', 'twothirds', 'uni2155', 'uni25D0', 'uni25D1', 'uni25D2', 'uni25D3', 'exclamdbl', 'uni2047', 'uni2048', 'uni2049', 'uni1E3E', 'uni1E3F', 'uni01F8', 'uni01F9', 'Euro', 'exclamdown', 'currency', 'brokenbar', 'copyright', 'ordfeminine', 'guillemotleft', 'registered', 'macron', 'uni0304', 'uni00B2', 'uni00B3', 'periodcentered', 'cedilla', 'uni00B9', 'ordmasculine', 'guillemotright', 'onequarter', 'onehalf', 'threequarters', 'questiondown', 'Agrave', 'Aacute', 'Acircumflex', 'Atilde', 'Adieresis', 'Aring', 'AE', 'Ccedilla', 'Egrave', 'Eacute', 'Ecircumflex', 'Edieresis', 'Igrave', 'Iacute', 'Icircumflex', 'Idieresis', 'Eth', 'Ntilde', 'Ograve', 'Oacute', 'Ocircumflex', 'Otilde', 'Odieresis', 'Oslash', 'Ugrave', 'Uacute', 'Ucircumflex', 'Udieresis', 'Yacute', 'Thorn', 'germandbls', 'agrave', 'aacute', 'acircumflex', 'atilde', 'adieresis', 'aring', 'ae', 'ccedilla', 'egrave', 'eacute', 'ecircumflex', 'edieresis', 'igrave', 'iacute', 'icircumflex', 'idieresis', 'eth', 'ntilde', 'ograve', 'oacute', 'ocircumflex', 'otilde', 'odieresis', 'oslash', 'ugrave', 'uacute', 'ucircumflex', 'udieresis', 'yacute', 'thorn', 'ydieresis', 'Amacron', 'Imacron', 'Umacron', 'Emacron', 'Omacron', 'amacron', 'imacron', 'umacron', 'emacron', 'omacron', 'Aogonek', 'breve', 'Lslash', 'Lcaron', 'Sacute', 'Scaron', 'Scedilla', 'Tcaron', 'Zacute', 'Zcaron', 'Zdotaccent', 'aogonek', 'ogonek', 'lslash', 'lcaron', 'sacute', 'caron', 'scaron', 'scedilla', 'tcaron', 'zacute', 'hungarumlaut', 'zcaron', 'zdotaccent', 'Racute', 'Abreve', 'Lacute', 'Cacute', 'Ccaron', 'Eogonek', 'Ecaron', 'Dcaron', 'Nacute', 'Ncaron', 'Ohungarumlaut', 'Rcaron', 'Uring', 'Uhungarumlaut', 'uni0162', 'racute', 'abreve', 'lacute', 'cacute', 'ccaron', 'eogonek', 'ecaron', 'dcaron', 'dcroat', 'nacute', 'ncaron', 'ohungarumlaut', 'rcaron', 'uring', 'uhungarumlaut', 'uni0163', 'dotaccent', 'Ccircumflex', 'Gcircumflex', 'Hcircumflex', 'Jcircumflex', 'Scircumflex', 'Ubreve', 'ccircumflex', 'gcircumflex', 'hcircumflex', 'jcircumflex', 'scircumflex', 'ubreve', 'uni0271', 'uni028B', 'uni027E', 'uni0283', 'uni0292', 'uni026C', 'uni026E', 'uni0279', 'uni0288', 'uni0256', 'uni0273', 'uni027D', 'uni0282', 'uni0290', 'uni027B', 'uni026D', 'uni025F', 'uni0272', 'uni029D', 'uni028E', 'uni0261', 'eng', 'uni0270', 'uni0281', 'hbar', 'uni0295', 'uni0294', 'uni0266', 'uni0298', 'uni01C2', 'uni0253', 'uni0257', 'uni0284', 'uni0260', 'uni0193', 'oe', 'OE', 'uni0268', 'uni0289', 'uni0258', 'uni0275', 'uni0259', 'uni025C', 'uni025E', 'uni0250', 'uni026F', 'uni028A', 'uni0264', 'uni028C', 'uni0254', 'uni0251', 'uni0252', 'uni028D', 'uni0265', 'uni02A2', 'uni02A1', 'uni0255', 'uni0291', 'uni027A', 'uni0267', 'uni025A', 'aeacute', 'uni1F70', 'uni1F71', 'uni1F72', 'uni1F73', 'uni0361', 'uni02C8', 'uni02CC', 'uni02D0', 'uni02D1', 'uni0306', 'uni203F', 'uni030B', 'acutecomb', 'uni030F', 'uni030C', 'uni0302', 'uni02E5', 'uni02E6', 'uni02E7', 'uni02E8', 'uni02E9', 'uni0325', 'uni032C', 'uni0339', 'uni031C', 'uni031F', 'uni0320', 'uni0308', 'uni033D', 'uni0329', 'uni032F', 'uni02DE', 'uni0324', 'uni0330', 'uni033C', 'uni0334', 'uni031D', 'uni031E', 'uni0318', 'uni0319', 'uni032A', 'uni033A', 'uni033B', 'tilde', 'uni031A', 'uni2042', 'uni00A0', 'glyph01248', 'glyph01249', 'glyph01250', 'glyph01251', 'uni00AD', 'glyph01253', 'minus', 'glyph01255', 'glyph01256', 'glyph01257', 'glyph01258', 'glyph01259', 'glyph01260', 'glyph01261', 'glyph01263', 'glyph01264', 'glyph01265', 'glyph01266', 'glyph01267', 'glyph01268', 'glyph01269', 'glyph01270', 'glyph01271', 'glyph01272', 'glyph01273', 'glyph01274', 'glyph01275', 'glyph01276', 'glyph01277', 'glyph01278', 'glyph01279', 'glyph01280', 'glyph01281', 'glyph01282', 'glyph01283', 'glyph01284', 'glyph01285', 'glyph01286', 'glyph01287', 'glyph01288', 'glyph01289', 'glyph01290', 'glyph01291', 'glyph01292', 'glyph01293', 'glyph01294', 'glyph01295', 'glyph01296', 'glyph01297', 'glyph01298', 'glyph01299', 'glyph01300', 'glyph01301', 'glyph01302', 'glyph01303', 'glyph01304', 'glyph01305', 'glyph01306', 'gravecomb', 'glyph01308', 'glyph01309', 'glyph01310', 'glyph01311', 'glyph01312', 'glyph01313', 'glyph01314', 'glyph01315', 'glyph01316', 'glyph01317', 'glyph01318', 'glyph01319', 'glyph01320', 'glyph01321', 'glyph01322', 'glyph01323', 'glyph01324', 'glyph01325', 'glyph01326', 'glyph01327', 'glyph01328', 'glyph01329', 'glyph01330', 'glyph01331', 'glyph01332', 'glyph01333', 'glyph01334', 'glyph01335', 'glyph01336', 'glyph01337', 'glyph01338', 'glyph01339', 'glyph01340', 'glyph01341', 'glyph01342', 'glyph01343', 'glyph01344', 'glyph01345', 'glyph01346', 'glyph01347', 'glyph01348', 'glyph01349', 'glyph01350', 'glyph01351', 'glyph01352', 'glyph01353', 'glyph01354', 'glyph01355', 'glyph01356', 'glyph01357', 'glyph01358', 'glyph01359', 'glyph01360', 'glyph01361', 'glyph01362', 'glyph01363', 'glyph01364', 'glyph01365', 'glyph01366', 'glyph01367', 'glyph01368', 'glyph01369', 'glyph01370', 'glyph01371', 'glyph01372', 'glyph01373', 'glyph01374', 'glyph01375', 'glyph01376', 'glyph01377', 'glyph01378', 'glyph01379', 'glyph01380', 'glyph01381', 'glyph01382', 'glyph01383', 'glyph01384', 'glyph01385', 'glyph01386', 'glyph01387', 'glyph01388', 'glyph01389', 'glyph01390', 'glyph01392', 'glyph01393', 'glyph01394', 'glyph01395', 'glyph01401', 'glyph01402', 'glyph01403', 'glyph01404', 'glyph01405', 'glyph01406', 'glyph01407', 'glyph01408', 'glyph01409', 'glyph01410', 'glyph01411', 'glyph01412', 'glyph01413', 'glyph01414', 'glyph01415', 'glyph01416', 'glyph01417', 'glyph01418', 'glyph01419', 'glyph01420', 'glyph01421', 'glyph01422', 'glyph01423', 'glyph01424', 'glyph01425', 'glyph01426', 'glyph01427', 'glyph01428', 'glyph01429', 'glyph01430', 'glyph01431', 'glyph01432', 'glyph01433', 'glyph01434', 'glyph01435', 'glyph01436', 'glyph01437', 'glyph01438', 'glyph01439', 'glyph01440', 'glyph01441', 'glyph01442', 'glyph01443', 'glyph01444', 'glyph01445', 'glyph01446', 'glyph01447', 'glyph01448', 'glyph01449', 'glyph01450', 'glyph01451', 'glyph01452', 'glyph01453', 'glyph01454', 'glyph01455', 'glyph01456', 'glyph01457', 'glyph01458', 'glyph01459', 'glyph01460', 'glyph01461', 'glyph01462', 'glyph01463', 'glyph01464', 'glyph01465', 'glyph01466', 'glyph01467', 'glyph01468', 'glyph01469', 'glyph01470', 'glyph01471', 'glyph01472', 'glyph01473', 'glyph01474', 'glyph01475', 'glyph01476', 'glyph01477', 'glyph01478', 'glyph01479', 'glyph01480', 'glyph01481', 'glyph01482', 'glyph01483', 'glyph01484', 'glyph01485', 'glyph01486', 'glyph01487', 'glyph01488', 'glyph01489', 'glyph01490', 'glyph01491', 'glyph01492', 'glyph01493', 'glyph01494', 'glyph01495', 'glyph01496', 'glyph01497', 'glyph01498', 'glyph01499', 'glyph01500', 'glyph01501', 'glyph01502', 'glyph01503', 'glyph01504', 'glyph01505', 'glyph01506', 'glyph01507', 'glyph01508', 'glyph01509', 'glyph01510', 'glyph01511', 'glyph01512', 'glyph01513', 'glyph01514', 'glyph01515', 'glyph01516', 'glyph01517', 'glyph01518', 'glyph01519', 'glyph01520', 'glyph01521', 'glyph01522', 'glyph01523', 'glyph01524', 'glyph01525', 'glyph01526', 'glyph01527', 'glyph01528', 'glyph01529', 'glyph01530', 'glyph01531', 'glyph01532', 'glyph01533', 'glyph01534', 'glyph01535', 'glyph01536', 'glyph01537', 'glyph01538', 'glyph01539', 'glyph01540', 'glyph01541', 'glyph01542', 'glyph01543', 'glyph01544', 'glyph01545', 'glyph01546', 'glyph01547', 'glyph01548', 'glyph01549', 'glyph01550', 'glyph01551', 'glyph01552', 'glyph01553', 'glyph01554', 'glyph01555', 'glyph01556', 'glyph01557', 'glyph01558', 'glyph01559', 'glyph01560', 'glyph01561', 'glyph01562', 'glyph01563', 'glyph01564', 'glyph01565', 'glyph01566', 'glyph01567', 'glyph01568', 'glyph01569', 'glyph01570', 'glyph01571', 'glyph01572', 'glyph01573', 'glyph01574', 'glyph01575', 'glyph01576', 'glyph01577', 'glyph01578', 'glyph01579', 'glyph01580', 'glyph01581', 'glyph01582', 'glyph01583', 'glyph01584', 'glyph01585', 'glyph01586', 'glyph01587', 'glyph01588', 'glyph01589', 'glyph01590', 'glyph01591', 'glyph01592', 'glyph01593', 'glyph01594', 'glyph01595', 'glyph01596', 'glyph01597', 'glyph01598', 'glyph01599', 'glyph01600', 'glyph01601', 'glyph01602', 'glyph01603', 'glyph01604', 'glyph01605', 'glyph01606', 'glyph01607', 'glyph01609', 'glyph01610', 'glyph01611', 'glyph01612', 'glyph01613', 'glyph01615', 'glyph01616', 'glyph01617', 'glyph01618', 'glyph01619', 'glyph01620', 'glyph01621', 'glyph01622', 'glyph01623', 'glyph01624', 'glyph01625', 'glyph01626', 'glyph01627', 'glyph01628', 'glyph01629', 'glyph01630', 'glyph01631', 'glyph01632', 'glyph01633', 'glyph01635', 'glyph01636', 'glyph01638', 'glyph01639', 'glyph01640', 'glyph01641', 'glyph01642', 'glyph01643', 'glyph01644', 'glyph01645', 'glyph01646', 'glyph01647', 'glyph01648', 'glyph01649', 'glyph01650', 'glyph01651', 'glyph01652', 'glyph01653', 'glyph01654', 'glyph01655', 'glyph01656', 'glyph01658', 'glyph01659', 'glyph01660', 'glyph01661', 'glyph01662', 'glyph01663', 'glyph01664', 'glyph01665', 'glyph01666', 'glyph01667', 'glyph01668', 'glyph01669', 'glyph01670', 'glyph01671', 'glyph01672', 'glyph01673', 'glyph01674', 'glyph01675', 'glyph01676', 'glyph01677', 'glyph01678', 'glyph01679', 'glyph01680', 'glyph01681', 'glyph01682', 'glyph01683', 'glyph01684', 'glyph01685', 'glyph01686', 'glyph01687', 'glyph01688', 'glyph01689', 'glyph01690', 'glyph01691', 'glyph01692', 'glyph01693', 'glyph01694', 'glyph01695', 'glyph01696', 'glyph01697', 'glyph01698', 'glyph01699', 'glyph01700', 'glyph01701', 'glyph01702', 'glyph01703', 'glyph01704', 'glyph01705', 'glyph01706', 'glyph01707', 'glyph01708', 'glyph01709', 'glyph01710', 'glyph01711', 'glyph01712', 'glyph01713', 'glyph01714', 'glyph01715', 'glyph01716', 'glyph01717', 'glyph01718', 'glyph01719', 'glyph01720', 'glyph01721', 'glyph01722', 'glyph01723', 'glyph01724', 'glyph01725', 'glyph01726', 'glyph01727', 'glyph01728', 'glyph01729', 'glyph01730', 'glyph01731', 'glyph01732', 'glyph01733', 'glyph01734', 'glyph01735', 'glyph01736', 'glyph01737', 'glyph01738', 'glyph01739', 'glyph01740', 'glyph01741', 'glyph01742', 'glyph01743', 'glyph01744', 'glyph01745', 'glyph01746', 'glyph01747', 'glyph01748', 'glyph01749', 'glyph01750', 'glyph01751', 'glyph01752', 'glyph01753', 'glyph01754', 'glyph01755', 'glyph01756', 'glyph01757', 'glyph01758', 'glyph01759', 'glyph01760', 'glyph01761', 'glyph01762', 'glyph01763', 'glyph01764', 'glyph01765', 'glyph01766', 'glyph01767', 'glyph01768', 'glyph01769', 'glyph01770', 'glyph01771', 'glyph01772', 'glyph01773', 'glyph01774', 'glyph01775', 'glyph01776', 'glyph01777', 'glyph01778', 'glyph01779', 'glyph01780', 'glyph01781', 'glyph01782', 'glyph01783', 'glyph01784', 'glyph01785', 'glyph01786', 'glyph01787', 'glyph01788', 'glyph01789', 'glyph01790', 'glyph01791', 'glyph01792', 'glyph01793', 'glyph01794', 'glyph01795', 'glyph01796', 'glyph01797', 'glyph01798', 'glyph01799', 'glyph01800', 'glyph01801', 'glyph01802', 'glyph01803', 'glyph01804', 'glyph01805', 'glyph01806', 'glyph01807', 'glyph01808', 'glyph01809', 'glyph01810', 'glyph01811', 'glyph01812', 'glyph01813', 'glyph01814', 'glyph01815', 'glyph01816', 'glyph01817', 'glyph01818', 'glyph01819', 'glyph01820', 'glyph01821', 'glyph01822', 'glyph01823', 'glyph01824', 'glyph01825', 'glyph01826', 'glyph01827', 'glyph01830', 'glyph01831', 'glyph01832', 'glyph01833', 'glyph01834', 'glyph01835', 'glyph01836', 'glyph01837', 'glyph01838', 'glyph01839', 'glyph01840', 'glyph01841', 'glyph01842', 'glyph01843', 'glyph01844', 'glyph01845', 'glyph01846', 'glyph01847', 'glyph01848', 'glyph01849', 'glyph01850', 'glyph01851', 'glyph01852', 'glyph01853', 'glyph01854', 'glyph01855', 'glyph01856', 'glyph01857', 'glyph01858', 'glyph01859', 'glyph01860', 'glyph01861', 'glyph01862', 'glyph01863', 'glyph01864', 'glyph01865', 'glyph01866', 'glyph01867', 'glyph01868', 'glyph01869', 'glyph01870', 'glyph01871', 'glyph01872', 'glyph01873', 'glyph01874', 'glyph01875', 'glyph01876', 'glyph01877', 'glyph01878', 'glyph01879', 'glyph01880', 'glyph01881', 'glyph01882', 'glyph01883', 'glyph01884', 'glyph01885', 'glyph01886', 'glyph01887', 'glyph01888', 'glyph01889', 'glyph01890', 'glyph01891', 'glyph01892', 'glyph01893', 'glyph01894', 'glyph01895', 'glyph01896', 'glyph01897', 'glyph01898', 'glyph01899', 'glyph12253', 'uni203E', 'glyph12255', 'glyph12256', 'glyph12259', 'cent', 'sterling', 'yen', 'logicalnot', 'emdash', 'glyph12283', 'glyph12284', 'glyph12285', 'glyph12286', 'glyph12287', 'glyph12288', 'glyph12289', 'glyph12290', 'glyph12291', 'glyph12292', 'glyph12293', 'glyph12294', 'glyph12295', 'glyph12296', 'glyph12297', 'glyph12298', 'glyph12299', 'glyph12300', 'glyph12301', 'glyph12302', 'glyph12303', 'glyph12304', 'glyph12305', 'glyph12306', 'glyph12307', 'glyph12308', 'glyph12309', 'glyph12310', 'glyph12311', 'glyph12312', 'glyph12313', 'glyph12314', 'glyph12315', 'glyph12316', 'uniFF61', 'uniFF62', 'uniFF63', 'uniFF64', 'uniFF65', 'uniFF66', 'uniFF67', 'uniFF68', 'uniFF69', 'uniFF6A', 'uniFF6B', 'uniFF6C', 'uniFF6D', 'uniFF6E', 'uniFF6F', 'uniFF70', 'uniFF71', 'uniFF72', 'uniFF73', 'uniFF74', 'uniFF75', 'uniFF76', 'uniFF77', 'uniFF78', 'uniFF79', 'uniFF7A', 'uniFF7B', 'uniFF7C', 'uniFF7D', 'uniFF7E', 'uniFF7F', 'uniFF80', 'uniFF81', 'uniFF82', 'uniFF83', 'uniFF84', 'uniFF85', 'uniFF86', 'uniFF87', 'uniFF88', 'uniFF89', 'uniFF8A', 'uniFF8B', 'uniFF8C', 'uniFF8D', 'uniFF8E', 'uniFF8F', 'uniFF90', 'uniFF91', 'uniFF92', 'uniFF93', 'uniFF94', 'uniFF95', 'uniFF96', 'uniFF97', 'uniFF98', 'uniFF99', 'uniFF9A', 'uniFF9B', 'uniFF9C', 'uniFF9D', 'uniFF9E', 'uniFF9F', 'glyph12855', 'glyph12856', 'glyph12857', 'glyph12858', 'glyph12859', 'glyph12860', 'glyph12861', 'glyph12862', 'glyph12863', 'glyph12864', 'glyph12865', 'glyph12866', 'glyph12867', 'glyph12868', 'glyph12869', 'glyph12870', 'glyph12871', 'glyph12874', 'glyph12875', 'glyph12876', 'glyph12877', 'glyph12878', 'glyph12879', 'glyph12880', 'glyph12881', 'glyph12882', 'glyph12883', 'glyph12884', 'glyph12885', 'glyph12886', 'glyph12887', 'glyph12888', 'glyph12889', 'glyph12890', 'glyph12891', 'glyph12892', 'glyph12893', 'glyph12894', 'glyph12895', 'glyph12896', 'glyph12897', 'glyph12898', 'glyph12899', 'glyph12900', 'glyph12901', 'glyph12902', 'glyph12903', 'glyph12904', 'glyph12905', 'glyph12906', 'glyph12907', 'glyph12908', 'glyph12909', 'glyph12910', 'glyph12911', 'glyph12912', 'glyph12913', 'glyph12914', 'glyph12915', 'glyph12916', 'glyph12917', 'glyph12918', 'glyph12919', 'glyph12920', 'glyph12921', 'glyph12922', 'glyph12923', 'glyph12924', 'glyph12925', 'glyph12926', 'glyph12927', 'glyph12928', 'glyph12929', 'glyph12930', 'glyph12931', 'glyph12932', 'glyph12933', 'glyph12934', 'glyph12935', 'glyph12936', 'glyph12937', 'glyph12938', 'glyph12939', 'glyph12940', 'glyph12941', 'glyph12942', 'glyph12943', 'glyph12944', 'glyph12945', 'glyph12946', 'glyph12947', 'glyph12948', 'glyph12949', 'glyph12950', 'glyph12951', 'glyph12952', 'glyph12953', 'glyph12954', 'glyph12955', 'glyph12956', 'glyph12957', 'glyph12958', 'glyph12959', 'glyph12960', 'glyph12961', 'glyph12962', 'glyph12963', 'glyph12964', 'glyph12965', 'glyph12966', 'glyph12967', 'glyph12968', 'glyph12969', 'glyph12970', 'glyph12971', 'glyph12972', 'glyph12973', 'glyph12974', 'glyph12975', 'glyph12976', 'glyph12977', 'glyph12978', 'glyph12979', 'glyph12980', 'glyph12981', 'glyph12982', 'glyph12983', 'glyph12984', 'glyph12985', 'glyph12986', 'glyph12987', 'glyph12988', 'glyph12989', 'glyph12990', 'glyph12991', 'glyph12992', 'glyph12993', 'glyph12994', 'glyph12995', 'glyph12996', 'glyph12997', 'glyph12998', 'glyph12999', 'glyph13000', 'glyph13001', 'glyph13002', 'glyph13003', 'glyph13004', 'glyph13005', 'glyph13006', 'glyph13007', 'glyph13008', 'glyph13009', 'glyph13010', 'glyph13011', 'glyph13012', 'glyph13013', 'glyph13014', 'glyph13015', 'glyph13016', 'glyph13017', 'glyph13018', 'glyph13019', 'glyph13020', 'glyph13021', 'glyph13022', 'glyph13023', 'glyph13024', 'glyph13025', 'glyph13026', 'glyph13027', 'glyph13028', 'glyph13029', 'glyph13030', 'glyph13031', 'glyph13032', 'glyph13033', 'glyph13034', 'glyph13035', 'glyph13036', 'glyph13037', 'glyph13038', 'glyph13039', 'glyph13040', 'glyph13041', 'glyph13042', 'glyph13043', 'glyph13044', 'glyph13045', 'glyph13046', 'glyph13047', 'glyph13048', 'glyph13576', 'glyph13671', 'glyph13672', 'glyph13673', 'glyph13674', 'glyph13675', 'glyph13676', 'glyph13677', 'glyph13678', 'glyph13679', 'glyph13680', 'glyph13681', 'glyph13682', 'glyph13683', 'glyph13684', 'glyph13685', 'glyph13686', 'glyph13687', 'glyph13688', 'glyph13689', 'glyph13690', 'glyph13691', 'glyph13692', 'glyph13693', 'glyph13694', 'glyph13695', 'glyph13696', 'glyph13697', 'glyph13698', 'glyph13699', 'glyph13700', 'glyph13701', 'glyph13702', 'glyph13703', 'glyph13704', 'glyph13705', 'glyph13706', 'glyph13707', 'glyph13708', 'glyph13709', 'glyph13710', 'glyph13711', 'glyph13712', 'glyph13713', 'glyph13714', 'glyph13715', 'glyph13716', 'glyph13717', 'glyph13718', 'glyph13719', 'glyph13720', 'glyph13721', 'glyph13722', 'glyph13723', 'glyph13724', 'glyph13725', 'glyph13726', 'glyph13727', 'glyph13728', 'glyph13729', 'glyph13730', 'glyph13731', 'glyph13732', 'glyph13733', 'glyph13734', 'glyph13735', 'glyph13736', 'glyph13737', 'glyph13738', 'glyph13739', 'glyph13740', 'glyph13741', 'glyph13813', 'Cdotaccent', 'Dcroat', 'Ebreve', 'Edotaccent', 'Gbreve', 'uni0122', 'Gdotaccent', 'Hbar', 'IJ', 'Ibreve', 'Idotaccent', 'Iogonek', 'Itilde', 'uni0136', 'uni013B', 'Ldot', 'uni0145', 'Eng', 'Obreve', 'uni0156', 'Tbar', 'Uogonek', 'Utilde', 'Wcircumflex', 'Ycircumflex', 'Ydieresis', 'cdotaccent', 'ebreve', 'edotaccent', 'gbreve', 'uni0123', 'gdotaccent', 'dotlessi', 'ibreve', 'ij', 'iogonek', 'itilde', 'uni0137', 'kgreenlandic', 'uni013C', 'ldot', 'napostrophe', 'uni0146', 'obreve', 'uni0157', 'longs', 'tbar', 'uogonek', 'utilde', 'wcircumflex', 'ycircumflex', 'uniFB01', 'uniFB02', 'uni2074', 'fraction', 'quotesinglbase', 'quotedblbase', 'guilsinglleft', 'guilsinglright', 'florin', 'greaterequal', 'lessequal', 'mu', 'lozenge', 'trademark', 'circumflex', 'ring', 'tonos', 'dieresistonos'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large.</summary><div>
* [com.google.fonts/check/file_size](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size)

* ⚠ **WARN** Font file is 5.9Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering?</summary><div>
* [com.google.fonts/check/gasp](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp)

* ⚠ **WARN** The gasp table has a range of 7 that may be unneccessary. [code: non-ffff-range]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary><div>
* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)

* ⚠ **WARN** GDEF table is missing, but it is mandatory to declare it on fonts that provide ligature glyphs because the caret (text cursor) positioning for each ligature must be provided in this table. [code: GDEF-missing]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- glyph01479
	- glyph13650
	- glyph01290
	- glyph01500
	- glyph01660
	- glyph13308
	- glyph01415
	- glyph01540
	- glyph01591
	- glyph01773 
	- And 1285 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: uni0403	Contours detected: 1	Expected: 2
	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 
	- And Glyph name: uni0403	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features?</summary><div>
* [com.google.fonts/check/cjk_chws_feature](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature)

* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table?</summary><div>
* [com.google.fonts/check/dsig](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig)

* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* AE (U+00C6): L<<524.0,665.0>--<524.0,1388.0>>/L<<524.0,1388.0>--<342.0,665.0>> = 14.129437561916355
	* m (U+006D): B<<504.0,1088.0>-<547.0,1021.0>-<549.0,936.0>>/B<<549.0,936.0>-<564.0,1008.0>-<591.0,1054.0>> = 13.116176212219232
	* m (U+006D): L<<246.0,1147.0>--<246.0,958.0>>/B<<246.0,958.0>-<265.0,1052.0>-<320.0,1105.0>> = 11.427101593945128
	* u28BC1 (U+28BC1): L<<801.0,-178.0>--<801.0,739.0>>/B<<801.0,739.0>-<737.0,483.0>-<614.0,236.0>> = 14.036243467926484
	* uni026F (U+026F): B<<521.0,18.0>-<477.0,87.0>-<476.0,170.0>>/B<<476.0,170.0>-<460.0,97.0>-<434.0,52.0>> = 13.05276961357937
	* uni026F (U+026F): L<<778.0,-41.0>--<778.0,147.0>>/B<<778.0,147.0>-<758.0,54.0>-<704.0,1.0>> = 12.13682445529227
	* uni0270 (U+0270): B<<521.0,119.0>-<477.0,188.0>-<476.0,270.0>>/B<<476.0,270.0>-<460.0,198.0>-<434.0,152.0>> = 13.227502092134934
	* uni0270 (U+0270): L<<778.0,-244.0>--<778.0,248.0>>/B<<778.0,248.0>-<759.0,155.0>-<704.0,101.0>> = 11.546690545927312
	* uni0271 (U+0271): B<<493.0,1088.0>-<536.0,1021.0>-<538.0,936.0>>/B<<538.0,936.0>-<553.0,1007.0>-<583.0,1055.0>> = 13.277209457436914
	* uni0271 (U+0271): L<<235.0,1147.0>--<235.0,958.0>>/B<<235.0,958.0>-<254.0,1052.0>-<309.0,1105.0>> = 11.427101593945128 and 182 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * u2074F (U+2074F): L<<1746.0,1251.0>--<1747.0,1416.0>>
 * u26FF8 (U+26FF8): L<<498.0,8.0>--<785.0,9.0>>
 * u273DB (U+273DB): L<<174.0,15.0>--<301.0,14.0>>
 * u273FE (U+273FE): L<<199.0,0.0>--<348.0,1.0>>
 * uni30BB (U+30BB): L<<809.0,865.0>--<807.0,387.0>>
 * uni30BC (U+30BC): L<<809.0,865.0>--<807.0,387.0>>
 * uni31FE (U+31FE): L<<627.0,340.0>--<626.0,531.0>>
 * uni32DD (U+32DD): L<<842.0,843.0>--<840.0,481.0>>
 * uni4453 (U+4453): L<<713.0,446.0>--<846.0,447.0>>
 * uni4E9F (U+4E9F): L<<984.0,1059.0>--<985.0,1174.0>> and 103 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 24 | 24 | 38 | 427 | 29 | 302 | 0 |
| 3% | 3% | 5% | 51% | 3% | 36% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**