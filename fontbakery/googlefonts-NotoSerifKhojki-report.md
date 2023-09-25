## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[2] Family checks</b></summary><div><details><summary>⚠ <b>WARN:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* ⚠ **WARN** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>⚠ <b>WARN:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* ⚠ **WARN** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[15] NotoSerifKhojki-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: 'KSSA'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, syriac, canadian-aboriginal, tai-le, coptic, math, malayalam
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, sundanese, lisu, kharoshthi, sora-sompeng, yi, cham, coptic, kayah-li, kaithi
 * U+261E WHITE RIGHT POINTING INDEX: try adding symbols
 * U+1123F KHOJKI LETTER QA: not included in any glyphset definition
 * U+11240 KHOJKI LETTER SHORT I: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `khojki`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* b_ra_iMatrakhoj
	* b_ra_iiMatrakhoj
	* b_ra_uMatrakhoj
	* b_rakhoj
	* ba_iMatrakhoj
	* ba_iiMatrakhoj
	* ba_uMatrakhoj
	* bakhoj
	* bb_ra_iMatrakhoj
	* bb_ra_iiMatrakhoj
	* bb_ra_uMatrakhoj
	* bb_rakhoj
	* bba_iMatrakhoj
	* bba_iiMatrakhoj
	* bba_uMatrakhoj
	* bbakhoj
	* bh_ra_iMatrakhoj
	* bh_ra_iiMatrakhoj
	* bh_ra_uMatrakhoj
	* bh_rakhoj
	* bha_iMatrakhoj
	* bha_iiMatrakhoj
	* bha_uMatrakhoj
	* bhakhoj
	* c_ra_iMatrakhoj
	* c_ra_iiMatrakhoj
	* c_ra_uMatrakhoj
	* c_rakhoj
	* cha_iMatrakhoj
	* cha_iiMatrakhoj
	* cha_uMatrakhoj
	* chakhoj
	* d_ra_uMatrakhoj
	* dd_ra_iMatrakhoj
	* dd_ra_iiMatrakhoj
	* dd_ra_uMatrakhoj
	* dd_rakhoj
	* dda_iMatrakhoj
	* dda_iiMatrakhoj
	* dda_uMatrakhoj
	* ddakhoj
	* ddha_uMatrakhoj
	* dh_ra_iMatrakhoj
	* dh_ra_iiMatrakhoj
	* dh_rakhoj
	* fourkhoj
	* g_na_iMatrakhoj
	* g_na_iiMatrakhoj
	* g_na_ra_iMatrakhoj
	* g_na_ra_iiMatrakhoj
	* g_na_ra_uMatrakhoj
	* g_na_rakhoj
	* g_na_uMatrakhoj
	* g_nakhoj
	* gg_ra_iMatrakhoj
	* gg_ra_iiMatrakhoj
	* gg_ra_uMatrakhoj
	* gg_rakhoj
	* h_ra_iMatrakhoj
	* h_ra_iiMatrakhoj
	* h_ra_uMatrakhoj
	* h_rakhoj
	* ha_uMatrakhoj
	* jj_ra_iMatrakhoj
	* jj_ra_iiMatrakhoj
	* jj_ra_uMatrakhoj
	* jj_rakhoj
	* jja_iMatrakhoj
	* jja_iiMatrakhoj
	* jja_uMatrakhoj
	* jjakhoj
	* k_ra_uMatrakhoj
	* k_ssa_iMatrakhoj
	* k_ssa_iiMatrakhoj
	* k_ssa_ra_iMatrakhoj
	* k_ssa_ra_iiMatrakhoj
	* k_ssa_ra_uMatrakhoj
	* k_ssa_rakhoj
	* k_ssa_uMatrakhoj
	* k_ssakhoj
	* ka_uMatrakhoj
	* kh_ra_iMatrakhoj
	* kh_ra_iiMatrakhoj
	* kh_ra_uMatrakhoj
	* kh_rakhoj
	* l_ra_iMatrakhoj
	* l_ra_iiMatrakhoj
	* l_ra_uMatrakhoj
	* l_rakhoj
	* la_iMatrakhoj
	* la_iiMatrakhoj
	* lla_iMatrakhoj
	* lla_iiMatrakhoj
	* lla_uMatrakhoj
	* llakhoj
	* m_ra_iMatrakhoj
	* m_ra_iiMatrakhoj
	* m_ra_uMatrakhoj
	* m_rakhoj
	* n_ra_iMatrakhoj
	* n_ra_iiMatrakhoj
	* n_ra_uMatrakhoj
	* n_rakhoj
	* na_iMatrakhoj
	* na_iiMatrakhoj
	* na_uMatrakhoj
	* nakhoj
	* nn_ra_iMatrakhoj
	* nn_ra_iiMatrakhoj
	* nn_ra_uMatrakhoj
	* nn_rakhoj
	* nna_iMatrakhoj
	* nna_iiMatrakhoj
	* nna_uMatrakhoj
	* nnakhoj
	* ph_ra_uMatrakhoj
	* q_ra_uMatrakhoj
	* qa_uMatrakhoj
	* ra_uMatrakhoj
	* s_ra_iMatrakhoj
	* s_ra_iiMatrakhoj
	* s_ra_uMatrakhoj
	* s_rakhoj
	* sixkhoj
	* t_ra_iMatrakhoj
	* t_ra_iiMatrakhoj
	* t_ra_uMatrakhoj
	* t_rakhoj
	* v_ra_iMatrakhoj
	* v_ra_iiMatrakhoj
	* v_ra_uMatrakhoj
	* v_rakhoj
	* va_iMatrakhoj
	* va_iiMatrakhoj
	* va_uMatrakhoj and vakhoj
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NullMark

	- dblsectionmark.alt

	- sha_eMatrakhoj

	- sha_iMatrakhoj

	- sha_iiMatrakhoj

	- sha_uMatrakhoj

	- shakhoj

	- sixkhoj.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 558:
plus, multiply
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+11235 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=187.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=339.5,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=187.0,Y=-1.0 (should be at baseline 0?)

	* J (U+004A): X=281.0,Y=-2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=321.0,Y=712.0 (should be at cap-height 714?)

	* bracketleft (U+005B): X=277.0,Y=712.0 (should be at cap-height 714?)

	* bracketright (U+005D): X=162.0,Y=712.0 (should be at cap-height 714?)

	* bracketright (U+005D): X=117.0,Y=712.0 (should be at cap-height 714?)

	* a (U+0061): X=265.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=310.0,Y=712.0 (should be at cap-height 714?)

	* s (U+0073): X=356.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=332.5,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=388.0,Y=712.0 (should be at cap-height 714?)

	* braceleft (U+007B): X=353.0,Y=712.0 (should be at cap-height 714?)

	* braceright (U+007D): X=153.0,Y=712.0 (should be at cap-height 714?)

	* braceright (U+007D): X=117.0,Y=712.0 (should be at cap-height 714?)

	* agrave (U+00E0): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=265.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=265.0,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=265.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=265.0,Y=-1.5 (should be at baseline 0?)

	* amacron (U+0101): X=265.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=265.0,Y=-1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=332.5,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=332.5,Y=-1.0 (should be at baseline 0?)

	* sixkhoj (U+0AEC): X=262.0,Y=2.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=408.0,Y=2.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=47.0,Y=716.0 (should be at cap-height 714?)

	* uni20B9 (U+20B9): X=520.0,Y=716.0 (should be at cap-height 714?)

	* uni20B9 (U+20B9): X=461.0,Y=2.0 (should be at baseline 0?)

	* aukhoj (U+11207): X=1112.0,Y=715.0 (should be at cap-height 714?)

	* kakhoj (U+11208): X=372.5,Y=-1.0 (should be at baseline 0?)

	* kakhoj (U+11208): X=616.0,Y=-1.0 (should be at baseline 0?)

	* kakhoj (U+11208): X=472.0,Y=1.0 (should be at baseline 0?)

	* ggakhoj (U+1120B): X=201.0,Y=-2.0 (should be at baseline 0?)

	* tthakhoj (U+11215): X=207.5,Y=2.0 (should be at baseline 0?)

	* nnakhoj (U+11218): X=244.0,Y=1.5 (should be at baseline 0?)

	* phakhoj (U+11220): X=527.0,Y=-2.0 (should be at baseline 0?)

	* rakhoj (U+11226): X=554.0,Y=1.5 (should be at baseline 0?)

	* auMatrakhoj (U+11233): X=126.0,Y=715.0 (should be at cap-height 714?)

	* Shaddakhoj (U+11237): X=-74.0,Y=712.0 (should be at cap-height 714?)

	* Shaddakhoj (U+11237): X=-74.0,Y=712.0 (should be at cap-height 714?)

	* qakhoj (U+1123F): X=408.5,Y=-1.0 (should be at baseline 0?)

	* qakhoj (U+1123F): X=652.0,Y=-1.0 (should be at baseline 0?)

	* qakhoj (U+1123F): X=508.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>>

	* sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifKhojki-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: 'KSSA'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, syriac, canadian-aboriginal, tai-le, coptic, math, malayalam
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, sundanese, lisu, kharoshthi, sora-sompeng, yi, cham, coptic, kayah-li, kaithi
 * U+261E WHITE RIGHT POINTING INDEX: try adding symbols
 * U+1123F KHOJKI LETTER QA: not included in any glyphset definition
 * U+11240 KHOJKI LETTER SHORT I: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `khojki`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* bb_ra_iMatrakhoj
	* bb_ra_iiMatrakhoj
	* bb_ra_uMatrakhoj
	* bb_rakhoj
	* bh_ra_iMatrakhoj
	* bh_ra_uMatrakhoj
	* bh_rakhoj
	* dd_ra_iMatrakhoj
	* dd_ra_iiMatrakhoj
	* dd_ra_uMatrakhoj
	* dd_rakhoj
	* dda_iiMatrakhoj
	* g_nakhoj
	* gg_ra_iMatrakhoj
	* gg_ra_iiMatrakhoj
	* gg_rakhoj
	* k_ssa_iMatrakhoj
	* k_ssa_iiMatrakhoj
	* k_ssa_ra_iMatrakhoj
	* k_ssa_ra_iiMatrakhoj
	* k_ssa_ra_uMatrakhoj
	* k_ssa_rakhoj
	* k_ssa_uMatrakhoj
	* k_ssakhoj
	* l_ra_iMatrakhoj
	* l_ra_iiMatrakhoj
	* l_ra_uMatrakhoj
	* l_rakhoj
	* nn_ra_iMatrakhoj
	* s_ra_uMatrakhoj
	* v_ra_iMatrakhoj
	* v_ra_iiMatrakhoj
	* v_ra_uMatrakhoj and v_rakhoj
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NullMark

	- dblsectionmark.alt

	- sha_eMatrakhoj

	- sha_iMatrakhoj

	- sha_iiMatrakhoj

	- sha_uMatrakhoj

	- shakhoj

	- sixkhoj.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 558:
plus, multiply
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+11235 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=284.0,Y=715.0 (should be at cap-height 714?)

	* parenright (U+0029): X=117.0,Y=715.0 (should be at cap-height 714?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=77.0,Y=715.0 (should be at cap-height 714?)

	* threekhoj (U+0AE9): X=294.0,Y=-2.0 (should be at baseline 0?)

	* threekhoj (U+0AE9): X=294.0,Y=-2.0 (should be at baseline 0?)

	* fourkhoj (U+0AEA): X=300.0,Y=-2.0 (should be at baseline 0?)

	* fourkhoj (U+0AEA): X=300.0,Y=-2.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=215.0,Y=715.0 (should be at cap-height 714?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblleft (U+201C): X=411.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=215.0,Y=715.0 (should be at cap-height 714?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

	* ekhoj (U+11204): X=507.0,Y=-2.0 (should be at baseline 0?)

	* ekhoj (U+11204): X=507.0,Y=-2.0 (should be at baseline 0?)

	* kakhoj (U+11208): X=691.5,Y=1.5 (should be at baseline 0?)

	* kakhoj (U+11208): X=603.0,Y=2.0 (should be at baseline 0?)

	* ngakhoj (U+1120D): X=294.0,Y=-2.0 (should be at baseline 0?)

	* ngakhoj (U+1120D): X=294.0,Y=-2.0 (should be at baseline 0?)

	* thakhoj (U+1121A): X=768.0,Y=-2.0 (should be at baseline 0?)

	* thakhoj (U+1121A): X=768.0,Y=-2.0 (should be at baseline 0?)

	* dddakhoj (U+1121C): X=274.5,Y=-1.0 (should be at baseline 0?)

	* pakhoj (U+1121F): X=507.0,Y=-2.0 (should be at baseline 0?)

	* pakhoj (U+1121F): X=507.0,Y=-2.0 (should be at baseline 0?)

	* phakhoj (U+11220): X=500.0,Y=2.0 (should be at baseline 0?)

	* sakhoj (U+11229): X=779.0,Y=-2.0 (should be at baseline 0?)

	* sakhoj (U+11229): X=779.0,Y=-2.0 (should be at baseline 0?)

	* sakhoj (U+11229): X=395.0,Y=-2.0 (should be at baseline 0?)

	* sakhoj (U+11229): X=395.0,Y=-2.0 (should be at baseline 0?)

	* qakhoj (U+1123F): X=715.5,Y=1.5 (should be at baseline 0?)

	* qakhoj (U+1123F): X=627.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 2 | 4 | 24 | 236 | 13 | 202 | 0 |
| 0% | 1% | 5% | 49% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
