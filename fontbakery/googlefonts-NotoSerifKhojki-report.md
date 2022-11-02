## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[3] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifKhojki/googlefonts/ttf', 'fonts/NotoSerifKhojki/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[10] NotoSerifKhojki-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/khojki.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifKhojki/googlefonts/ttf/NotoSerifKhojki-Bold.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/khojki.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑈙𑈯𑈧𑈵𑈥</span> (Don't delete JA/TA/LA before YA)</li>


<pre>Expected: None</pre>



<pre>Got     : ta_uMatrakhoj=0+721|lakhoj=2+673|yakarkhoj=2+709</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2103 2856" transform="matrix(1 0 0 -1 0 0)">
<path d="M357.0,-183.0Q258.0,-183.0 176.0,-129.0Q94.0,-75.0 38.0,16.0L47.0,92.0L61.0,95.0Q115.0,16.0 179.0,-23.5Q243.0,-63.0 310.0,-63.0Q373.0,-63.0 422.5,-30.0Q472.0,3.0 506.5,59.5Q541.0,116.0 559.5,187.0Q578.0,258.0 578.0,333.0Q578.0,398.0 562.5,428.0Q547.0,458.0 521.0,458.0Q492.0,458.0 460.5,427.5Q429.0,397.0 400.0,347.0Q371.0,297.0 349.0,238.0Q354.0,199.0 354.0,168.0Q354.0,116.0 339.0,83.5Q324.0,51.0 292.0,51.0Q268.0,51.0 242.0,66.5Q216.0,82.0 197.5,106.0Q179.0,130.0 179.0,156.0Q179.0,194.0 194.5,242.0Q210.0,290.0 234.0,338.0Q219.0,378.0 206.5,397.5Q194.0,417.0 181.0,423.0Q168.0,429.0 150.0,429.0Q130.0,429.0 105.0,421.5Q80.0,414.0 59.0,401.0Q43.0,420.0 31.5,445.5Q20.0,471.0 20.0,492.0Q20.0,527.0 43.5,543.5Q67.0,560.0 107.0,560.0Q160.0,560.0 196.5,519.0Q233.0,478.0 265.0,394.0Q284.0,423.0 303.0,449.0Q349.0,510.0 392.5,540.0Q436.0,570.0 484.0,570.0Q544.0,570.0 586.0,527.5Q628.0,485.0 649.5,413.5Q671.0,342.0 671.0,256.0Q671.0,162.0 649.0,82.0Q627.0,2.0 585.5,-57.5Q544.0,-117.0 486.5,-150.0Q429.0,-183.0 357.0,-183.0Z"  transform="translate(0, 947)"/>
<path d="M230.0,209.0L77.0,289.0L77.0,306.0Q121.0,325.0 158.5,350.5Q196.0,376.0 219.0,403.5Q242.0,431.0 242.0,456.0Q242.0,497.0 194.0,497.0Q158.0,497.0 116.5,476.5Q75.0,456.0 40.0,424.0Q-15.0,471.0 -15.0,518.0Q-15.0,560.0 25.5,580.5Q66.0,601.0 129.0,601.0Q189.0,601.0 240.5,576.0Q292.0,551.0 323.0,509.5Q354.0,468.0 354.0,418.0Q354.0,358.0 317.0,309.0L475.0,309.0Q476.0,336.0 476.0,363.0Q476.0,419.0 469.5,483.0Q463.0,547.0 449.0,613.0L560.0,613.0Q580.0,529.0 589.0,449.5Q598.0,370.0 598.0,293.0Q598.0,220.0 590.5,139.5Q583.0,59.0 567.0,-13.0L529.0,-22.0Q521.0,-16.0 503.0,4.0Q485.0,24.0 467.5,47.0Q450.0,70.0 441.0,85.0Q457.0,146.0 466.0,209.0L230.0,209.0Z"  transform="translate(721, 947)"/>
<path d="M562.0,-22.0Q553.0,-15.0 533.5,6.5Q514.0,28.0 494.5,53.0Q475.0,78.0 466.0,95.0Q480.0,124.0 495.0,163.0Q510.0,202.0 523.0,245.5Q536.0,289.0 544.0,331.5Q552.0,374.0 552.0,410.0Q552.0,444.0 539.0,466.5Q526.0,489.0 494.0,489.0Q465.0,489.0 422.0,472.0Q411.0,482.0 396.0,499.5Q381.0,517.0 366.5,535.5Q352.0,554.0 342.0,568.0L346.0,584.0Q369.0,597.0 397.0,604.5Q425.0,612.0 450.0,612.0Q503.0,612.0 549.5,574.5Q596.0,537.0 625.0,470.5Q654.0,404.0 654.0,318.0Q654.0,285.0 649.5,242.0Q645.0,199.0 637.0,153.0Q629.0,107.0 619.5,63.5Q610.0,20.0 600.0,-13.0L562.0,-22.0ZM235.0,95.0Q192.0,95.0 151.5,113.5Q111.0,132.0 79.0,164.5Q47.0,197.0 28.5,238.0Q10.0,279.0 10.0,324.0Q10.0,381.0 37.5,425.5Q65.0,470.0 110.0,495.5Q155.0,521.0 207.0,521.0Q249.0,521.0 288.0,503.0Q327.0,485.0 357.5,453.0Q388.0,421.0 405.5,380.0Q423.0,339.0 423.0,293.0Q423.0,238.0 397.5,193.0Q372.0,148.0 329.5,121.5Q287.0,95.0 235.0,95.0ZM194.0,210.0Q225.0,210.0 253.0,226.5Q281.0,243.0 299.0,271.0Q317.0,299.0 317.0,331.0Q317.0,366.0 299.5,384.0Q282.0,402.0 250.0,402.0Q218.0,402.0 188.0,385.0Q158.0,368.0 139.5,340.0Q121.0,312.0 121.0,279.0Q121.0,249.0 140.5,229.5Q160.0,210.0 194.0,210.0Z"  transform="translate(1394, 947)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.856x (1856) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Nukta_aiMatrakhoj

	- Nukta_auMatrakhoj

	- Nukta_eMatrakhoj

	- Nukta_oMatrakhoj

	- NullMark

	- dblsectionmark.alt

	- k_ra_uMatrakhoj.alt

	- rakar_rVocalicMatra

	- sh_ra_iMatrakhoj

	- sh_ra_iiMatrakhoj 

	- And 3 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* And 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 

	* And ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>> 

	* And sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSerifKhojki-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/khojki.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifKhojki/googlefonts/ttf/NotoSerifKhojki-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/khojki.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑈙𑈯𑈧𑈵𑈥</span> (Don't delete JA/TA/LA before YA)</li>


<pre>Expected: None</pre>



<pre>Got     : ta_uMatrakhoj=0+704|lakhoj=2+636|yakarkhoj=2+663</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2003 2856" transform="matrix(1 0 0 -1 0 0)">
<path d="M352.0,-159.0Q290.0,-159.0 232.5,-133.0Q175.0,-107.0 127.5,-64.5Q80.0,-22.0 47.0,27.0L53.0,82.0L60.0,84.0Q110.0,13.0 176.5,-32.0Q243.0,-77.0 316.0,-77.0Q381.0,-77.0 429.5,-42.0Q478.0,-7.0 510.0,51.5Q542.0,110.0 558.0,182.0Q574.0,254.0 574.0,327.0Q574.0,366.0 567.5,400.0Q561.0,434.0 547.0,455.0Q533.0,476.0 508.0,476.0Q482.0,476.0 456.0,456.0Q430.0,436.0 405.5,403.0Q381.0,370.0 360.5,331.0Q340.0,292.0 324.0,253.0Q326.0,235.0 326.5,217.0Q327.0,199.0 327.0,183.0Q327.0,134.0 317.0,99.0Q307.0,64.0 282.0,64.0Q265.0,64.0 245.0,74.5Q225.0,85.0 211.5,102.5Q198.0,120.0 198.0,141.0Q198.0,174.0 209.5,214.5Q221.0,255.0 238.0,296.0Q219.0,366.0 202.5,397.5Q186.0,429.0 170.5,438.0Q155.0,447.0 138.0,447.0Q119.0,447.0 98.0,440.5Q77.0,434.0 61.0,425.0Q51.0,439.0 43.0,456.0Q35.0,473.0 35.0,489.0Q35.0,510.0 54.5,524.0Q74.0,538.0 106.0,538.0Q135.0,538.0 162.0,522.5Q189.0,507.0 214.0,466.0Q239.0,425.0 263.0,348.0Q286.0,393.0 312.0,431.0Q345.0,480.0 385.5,515.5Q426.0,551.0 476.0,551.0Q528.0,551.0 564.0,515.0Q600.0,479.0 619.5,414.0Q639.0,349.0 639.0,261.0Q639.0,183.0 621.5,108.0Q604.0,33.0 568.0,-27.0Q532.0,-87.0 478.0,-123.0Q424.0,-159.0 352.0,-159.0Z"  transform="translate(0, 947)"/>
<path d="M214.0,224.0L88.0,279.0L88.0,293.0Q158.0,325.0 201.5,369.0Q245.0,413.0 245.0,455.0Q245.0,481.0 227.5,496.0Q210.0,511.0 181.0,511.0Q152.0,511.0 114.5,496.5Q77.0,482.0 40.0,448.0Q23.0,464.0 11.5,480.5Q0.0,497.0 0.0,514.0Q0.0,537.0 19.0,552.0Q38.0,567.0 66.5,574.0Q95.0,581.0 123.0,581.0Q173.0,581.0 217.0,560.5Q261.0,540.0 288.5,504.0Q316.0,468.0 316.0,421.0Q316.0,390.0 301.5,357.0Q287.0,324.0 255.0,294.0L468.0,294.0Q469.0,317.0 469.0,340.0Q469.0,408.0 460.5,472.5Q452.0,537.0 437.0,600.0L513.0,600.0Q531.0,536.0 541.0,454.5Q551.0,373.0 551.0,293.0Q551.0,217.0 542.5,140.0Q534.0,63.0 517.0,0.0L493.0,-9.0Q486.0,-2.0 473.0,17.5Q460.0,37.0 449.5,57.0Q439.0,77.0 437.0,83.0Q455.0,151.0 463.0,224.0L214.0,224.0Z"  transform="translate(704, 947)"/>
<path d="M519.0,-9.0Q514.0,-4.0 504.0,9.5Q494.0,23.0 483.5,38.5Q473.0,54.0 465.5,67.5Q458.0,81.0 457.0,86.0Q478.0,140.0 494.5,196.5Q511.0,253.0 520.5,306.5Q530.0,360.0 530.0,403.0Q530.0,457.0 513.0,483.0Q496.0,509.0 455.0,509.0Q427.0,509.0 391.0,498.0Q376.0,511.0 357.0,532.0Q338.0,553.0 326.0,569.0L327.0,575.0Q344.0,585.0 369.0,592.5Q394.0,600.0 416.0,600.0Q462.0,600.0 503.5,567.5Q545.0,535.0 571.5,476.5Q598.0,418.0 598.0,339.0Q598.0,305.0 593.5,260.5Q589.0,216.0 581.0,168.0Q573.0,120.0 563.5,76.0Q554.0,32.0 544.0,0.0L519.0,-9.0ZM217.0,122.0Q177.0,122.0 141.0,140.0Q105.0,158.0 78.0,187.5Q51.0,217.0 35.5,254.0Q20.0,291.0 20.0,328.0Q20.0,374.0 42.5,413.0Q65.0,452.0 103.5,475.5Q142.0,499.0 189.0,499.0Q241.0,499.0 284.5,470.5Q328.0,442.0 354.0,396.5Q380.0,351.0 380.0,299.0Q380.0,253.0 359.0,212.5Q338.0,172.0 301.5,147.0Q265.0,122.0 217.0,122.0ZM183.0,200.0Q217.0,200.0 244.5,218.5Q272.0,237.0 288.0,266.5Q304.0,296.0 304.0,330.0Q304.0,368.0 284.0,393.5Q264.0,419.0 224.0,419.0Q196.0,419.0 167.0,404.0Q138.0,389.0 119.0,360.5Q100.0,332.0 100.0,291.0Q100.0,248.0 122.5,224.0Q145.0,200.0 183.0,200.0Z"  transform="translate(1340, 947)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.856x (1856) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Nukta_aiMatrakhoj

	- Nukta_auMatrakhoj

	- Nukta_eMatrakhoj

	- Nukta_oMatrakhoj

	- NullMark

	- dblsectionmark.alt

	- k_ra_uMatrakhoj.alt

	- rakar_rVocalicMatra

	- sh_ra_iMatrakhoj

	- sh_ra_iiMatrakhoj 

	- And 3 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* And 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[11] NotoSerifKhojki[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/khojki.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifKhojki/googlefonts/variable-ttf/NotoSerifKhojki[wght].ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/khojki.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑈙𑈯𑈧𑈵𑈥</span> (Don't delete JA/TA/LA before YA)</li>


<pre>Expected: None</pre>



<pre>Got     : ta_uMatrakhoj=0+704|lakhoj=2+636|yakarkhoj=2+663</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2003 2856" transform="matrix(1 0 0 -1 0 0)">
<path d="M352.0,-159.0Q290.0,-159.0 232.5,-133.0Q175.0,-107.0 127.5,-64.5Q80.0,-22.0 47.0,27.0L53.0,82.0L60.0,84.0Q110.0,13.0 176.5,-32.0Q243.0,-77.0 316.0,-77.0Q381.0,-77.0 429.5,-42.0Q478.0,-7.0 510.0,51.5Q542.0,110.0 558.0,182.0Q574.0,254.0 574.0,327.0Q574.0,366.0 567.5,400.0Q561.0,434.0 547.0,455.0Q533.0,476.0 508.0,476.0Q480.0,476.0 451.0,451.5Q422.0,427.0 395.5,388.5Q369.0,350.0 347.5,305.5Q326.0,261.0 312.0,220.0L323.0,266.0Q325.0,245.0 326.0,224.0Q327.0,203.0 327.0,183.0Q327.0,134.0 317.0,99.0Q307.0,64.0 282.0,64.0Q265.0,64.0 245.0,74.5Q225.0,85.0 211.5,102.5Q198.0,120.0 198.0,141.0Q198.0,183.0 215.5,235.5Q233.0,288.0 259.0,339.5Q285.0,391.0 312.0,431.0Q345.0,480.0 385.5,515.5Q426.0,551.0 476.0,551.0Q528.0,551.0 564.0,515.0Q600.0,479.0 619.5,414.0Q639.0,349.0 639.0,261.0Q639.0,183.0 621.5,108.0Q604.0,33.0 568.0,-27.0Q532.0,-87.0 478.0,-123.0Q424.0,-159.0 352.0,-159.0ZM254.0,238.0Q236.0,311.0 221.0,353.0Q206.0,395.0 192.5,415.0Q179.0,435.0 166.0,441.0Q153.0,447.0 138.0,447.0Q119.0,447.0 98.0,440.5Q77.0,434.0 61.0,425.0Q51.0,439.0 43.0,456.0Q35.0,473.0 35.0,489.0Q35.0,510.0 55.0,524.0Q75.0,538.0 106.0,538.0Q140.0,538.0 170.0,517.5Q200.0,497.0 228.0,441.0Q256.0,385.0 283.0,278.0L254.0,238.0Z"  transform="translate(0, 947)"/>
<path d="M214.0,224.0L88.0,279.0L88.0,293.0Q135.0,315.0 170.0,342.0Q205.0,369.0 225.0,398.0Q245.0,427.0 245.0,455.0Q245.0,481.0 227.5,496.0Q210.0,511.0 181.0,511.0Q152.0,511.0 114.5,496.5Q77.0,482.0 40.0,448.0Q23.0,464.0 11.5,480.5Q0.0,497.0 0.0,514.0Q0.0,537.0 19.0,552.0Q38.0,567.0 66.5,574.0Q95.0,581.0 123.0,581.0Q173.0,581.0 217.0,560.5Q261.0,540.0 288.5,504.0Q316.0,468.0 316.0,421.0Q316.0,384.0 295.0,344.5Q274.0,305.0 227.0,270.0L206.0,294.0L499.0,294.0L490.0,224.0L214.0,224.0ZM493.0,-9.0Q486.0,-2.0 473.0,17.5Q460.0,37.0 449.5,57.0Q439.0,77.0 437.0,83.0Q453.0,144.0 461.0,209.5Q469.0,275.0 469.0,340.0Q469.0,408.0 460.5,472.5Q452.0,537.0 437.0,600.0L513.0,600.0Q531.0,536.0 541.0,454.5Q551.0,373.0 551.0,293.0Q551.0,217.0 542.5,140.0Q534.0,63.0 517.0,0.0L493.0,-9.0Z"  transform="translate(704, 947)"/>
<path d="M519.0,-9.0Q514.0,-4.0 504.0,9.5Q494.0,23.0 483.5,38.5Q473.0,54.0 465.5,67.5Q458.0,81.0 457.0,86.0Q472.0,127.0 485.5,169.0Q499.0,211.0 509.0,252.5Q519.0,294.0 524.5,332.0Q530.0,370.0 530.0,403.0Q530.0,457.0 513.0,483.0Q496.0,509.0 455.0,509.0Q427.0,509.0 391.0,498.0Q381.0,507.0 369.0,519.0Q357.0,531.0 345.5,544.5Q334.0,558.0 326.0,569.0L327.0,575.0Q344.0,585.0 369.0,592.5Q394.0,600.0 416.0,600.0Q462.0,600.0 503.5,567.5Q545.0,535.0 571.5,476.5Q598.0,418.0 598.0,339.0Q598.0,305.0 593.5,260.5Q589.0,216.0 581.0,168.0Q573.0,120.0 563.5,76.0Q554.0,32.0 544.0,0.0L519.0,-9.0ZM217.0,122.0Q177.0,122.0 141.0,140.0Q105.0,158.0 78.0,187.5Q51.0,217.0 35.5,254.0Q20.0,291.0 20.0,328.0Q20.0,374.0 42.5,413.0Q65.0,452.0 103.5,475.5Q142.0,499.0 189.0,499.0Q228.0,499.0 262.5,482.5Q297.0,466.0 323.5,438.0Q350.0,410.0 365.0,374.0Q380.0,338.0 380.0,299.0Q380.0,253.0 359.0,212.5Q338.0,172.0 301.5,147.0Q265.0,122.0 217.0,122.0ZM183.0,200.0Q217.0,200.0 244.5,218.5Q272.0,237.0 288.0,266.5Q304.0,296.0 304.0,330.0Q304.0,368.0 284.0,393.5Q264.0,419.0 224.0,419.0Q196.0,419.0 167.0,404.0Q138.0,389.0 119.0,360.5Q100.0,332.0 100.0,291.0Q100.0,248.0 122.5,224.0Q145.0,200.0 183.0,200.0Z"  transform="translate(1340, 947)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.856x (1856) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Nukta_aiMatrakhoj

	- Nukta_auMatrakhoj

	- Nukta_eMatrakhoj

	- Nukta_oMatrakhoj

	- NullMark

	- dblsectionmark.alt

	- k_ra_uMatrakhoj.alt

	- rakar_rVocalicMatra

	- sh_ra_iMatrakhoj

	- sh_ra_iiMatrakhoj 

	- And 3 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
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

	* f (U+0066): X=331.0,Y=712.5 (should be at cap-height 714?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=66.5,Y=713.5 (should be at cap-height 714?) 

	* And 44 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 6 | 23 | 319 | 20 | 280 | 0 |
| 0% | 1% | 4% | 49% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
