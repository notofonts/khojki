## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[13] NotoSerifKhojki[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed to access: <a href="http://namecheck.fontdata.com">http://namecheck.fontdata.com</a>.
This check relies on the external service <a href="http://namecheck.fontdata.com">http://namecheck.fontdata.com</a> via the internet. While the service cannot be reached or does not respond this check is broken.</p>
<pre><code>	You can exclude this check with the command line option:
	-x com.google.fonts/check/fontdata_namecheck

	Or you can wait until the service is available again.
	If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

	Original error message:
	&lt;class 'requests.exceptions.ReadTimeout'&gt;
</code></pre>
 [code: namecheck-service]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/khojki.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: 𑈈𑈵𑈩𑈶𑈯 𑈈𑈵𑈩𑈶‍𑈵𑈦 (Do KSSA first (#8))</p>
<pre><code>Expected: None
Got     : k_ssa_uMatrakhoj=0+760|space=5+260|k_ssakhoj=6+681|space=6+0|halantkhoj=6@3,31+0|rakhoj=12+568
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -447 2319 1856" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g35" d="M275.0,27.0Q234.0,26.0 196.0,41.0Q158.0,56.0 128.5,81.0Q99.0,106.0 82.0,137.5Q65.0,169.0 65.0,202.0Q65.0,237.0 83.0,260.5Q101.0,284.0 129.0,301.5Q157.0,319.0 187.0,335.0Q211.0,348.0 242.0,368.0Q273.0,388.0 296.0,415.5Q319.0,443.0 319.0,477.0Q319.0,505.0 301.5,523.5Q284.0,542.0 255.0,542.0Q222.0,542.0 201.5,517.0Q181.0,492.0 181.0,451.0Q181.0,408.0 204.0,376.5Q227.0,345.0 265.5,328.0Q304.0,311.0 349.0,311.0Q382.0,311.0 416.5,319.0Q451.0,327.0 483.5,340.5Q516.0,354.0 542.5,369.0Q569.0,384.0 585.0,399.0L606.0,312.0Q582.0,298.0 545.5,283.0Q509.0,268.0 468.5,257.5Q428.0,247.0 391.0,247.0Q341.0,247.0 290.0,267.0Q239.0,287.0 196.0,321.5Q153.0,356.0 127.0,399.5Q101.0,443.0 101.0,489.0Q101.0,541.0 135.0,572.5Q169.0,604.0 222.0,604.0Q268.0,604.0 305.5,581.5Q343.0,559.0 365.5,523.0Q388.0,487.0 388.0,446.0Q388.0,410.0 370.0,378.5Q352.0,347.0 320.0,321.0Q288.0,295.0 247.0,274.0Q213.0,257.0 189.0,243.0Q165.0,229.0 152.5,213.5Q140.0,198.0 140.0,176.0Q140.0,141.0 166.5,125.0Q193.0,109.0 227.0,109.0Q270.0,109.0 307.0,129.0L246.0,92.0Q256.0,117.0 267.5,140.0Q279.0,163.0 293.5,178.0Q308.0,193.0 327.0,193.0Q347.0,193.0 364.5,178.0Q382.0,163.0 393.5,142.5Q405.0,122.0 405.0,106.0Q405.0,87.0 387.5,69.0Q370.0,51.0 341.0,39.5Q312.0,28.0 275.0,27.0ZM500.0,-341.0Q424.0,-341.0 350.5,-319.5Q277.0,-298.0 211.0,-258.0Q145.0,-218.0 91.0,-163.5Q37.0,-109.0 0.0,-43.0L11.0,12.0L20.0,15.0Q68.0,-64.0 134.0,-124.5Q200.0,-185.0 282.0,-219.5Q364.0,-254.0 459.0,-254.0Q505.0,-254.0 549.5,-245.5Q594.0,-237.0 630.5,-219.5Q667.0,-202.0 688.5,-175.5Q710.0,-149.0 710.0,-114.0Q710.0,-86.0 695.5,-67.5Q681.0,-49.0 653.0,-49.0Q634.0,-49.0 612.5,-59.0Q591.0,-69.0 565.0,-89.0Q543.0,-76.0 523.0,-60.5Q503.0,-45.0 492.0,-31.0Q519.0,-5.0 547.5,8.0Q576.0,21.0 606.0,21.0Q638.0,21.0 668.5,7.5Q699.0,-6.0 724.5,-30.0Q750.0,-54.0 765.0,-86.0Q780.0,-118.0 780.0,-155.0Q780.0,-213.0 742.0,-255.0Q704.0,-297.0 640.5,-319.0Q577.0,-341.0 500.0,-341.0ZM375.0,-164.0Q328.0,-164.0 297.0,-140.0Q266.0,-116.0 250.5,-77.0Q235.0,-38.0 235.0,7.0Q235.0,18.0 236.0,31.5Q237.0,45.0 240.0,59.0L303.0,50.0Q294.0,33.0 290.0,15.5Q286.0,-2.0 286.0,-18.0Q286.0,-48.0 300.5,-64.0Q315.0,-80.0 350.0,-80.0Q373.0,-80.0 397.0,-73.0Q421.0,-66.0 442.0,-53.0Q450.0,-66.0 456.0,-85.0Q462.0,-104.0 462.0,-115.0Q462.0,-140.0 434.0,-152.0Q406.0,-164.0 375.0,-164.0ZM564.0,-19.0Q574.0,42.0 579.0,113.5Q584.0,185.0 584.0,259.0Q584.0,351.0 575.5,440.0Q567.0,529.0 550.0,600.0L626.0,600.0Q646.0,518.0 654.5,428.5Q663.0,339.0 663.0,253.0Q663.0,183.0 659.0,114.0Q655.0,45.0 648.0,-18.0L564.0,-19.0Z"/> <path id="g3" d=""/> <path id="g32" d="M261.0,-19.0Q216.0,-19.0 176.5,-1.5Q137.0,16.0 107.5,44.5Q78.0,73.0 61.5,108.0Q45.0,143.0 45.0,177.0Q45.0,207.0 58.5,230.5Q72.0,254.0 99.5,277.5Q127.0,301.0 168.0,329.0Q203.0,353.0 233.0,376.0Q263.0,399.0 281.0,424.0Q299.0,449.0 299.0,477.0Q299.0,505.0 281.5,523.5Q264.0,542.0 235.0,542.0Q202.0,542.0 181.5,517.0Q161.0,492.0 161.0,451.0Q161.0,408.0 184.0,374.0Q207.0,340.0 246.0,320.5Q285.0,301.0 332.0,301.0Q369.0,301.0 408.0,313.0Q447.0,325.0 481.5,345.0Q516.0,365.0 537.0,389.0L556.0,300.0Q533.0,283.0 501.0,268.5Q469.0,254.0 435.5,245.5Q402.0,237.0 373.0,237.0Q322.0,237.0 270.5,259.0Q219.0,281.0 176.0,317.5Q133.0,354.0 107.0,398.5Q81.0,443.0 81.0,489.0Q81.0,541.0 115.0,572.5Q149.0,604.0 202.0,604.0Q248.0,604.0 285.5,581.5Q323.0,559.0 345.5,523.0Q368.0,487.0 368.0,445.0Q368.0,406.0 348.0,375.5Q328.0,345.0 296.0,319.5Q264.0,294.0 227.0,269.0Q184.0,240.0 151.5,212.0Q119.0,184.0 119.0,141.0Q119.0,101.0 148.5,83.0Q178.0,65.0 215.0,65.0Q228.0,65.0 241.0,67.0Q254.0,69.0 266.0,72.0L234.0,46.0Q244.0,71.0 255.0,94.0Q266.0,117.0 280.0,132.0Q294.0,147.0 313.0,147.0Q333.0,147.0 350.5,132.0Q368.0,117.0 379.5,96.5Q391.0,76.0 391.0,60.0Q391.0,41.0 373.5,23.0Q356.0,5.0 327.0,-6.5Q298.0,-18.0 261.0,-19.0ZM374.0,-240.0Q330.0,-240.0 295.5,-216.0Q261.0,-192.0 241.5,-148.5Q222.0,-105.0 222.0,-49.0Q222.0,-28.0 225.5,-5.0Q229.0,18.0 237.0,45.0L312.0,28.0Q291.0,3.0 282.0,-23.5Q273.0,-50.0 273.0,-76.0Q273.0,-111.0 290.0,-133.5Q307.0,-156.0 349.0,-156.0Q375.0,-156.0 402.0,-148.0Q429.0,-140.0 451.0,-127.0Q458.0,-140.0 463.0,-159.0Q468.0,-178.0 468.0,-189.0Q468.0,-205.0 453.5,-216.5Q439.0,-228.0 417.0,-234.0Q395.0,-240.0 374.0,-240.0ZM558.0,-9.0Q551.0,-2.0 538.0,17.5Q525.0,37.0 514.5,57.0Q504.0,77.0 502.0,83.0Q518.0,144.0 526.0,209.5Q534.0,275.0 534.0,340.0Q534.0,408.0 525.5,472.5Q517.0,537.0 502.0,600.0L578.0,600.0Q596.0,536.0 606.0,454.5Q616.0,373.0 616.0,293.0Q616.0,217.0 607.5,140.0Q599.0,63.0 582.0,0.0L558.0,-9.0Z"/> <path id="g316" d="M152.0,-320.0Q118.0,-280.0 83.0,-243.0Q48.0,-206.0 13.5,-178.0Q-21.0,-150.0 -53.0,-138.0L-129.0,-166.0L-224.0,-127.0L-223.0,-111.0Q-197.0,-96.0 -162.0,-84.5Q-127.0,-73.0 -94.0,-73.0Q-50.0,-73.0 -5.0,-102.0Q40.0,-131.0 87.5,-181.5Q135.0,-232.0 185.0,-295.0L152.0,-320.0Z"/> <path id="g235" d="M496.0,-104.0Q439.0,-104.0 394.5,-87.5Q350.0,-71.0 308.0,-37.0Q264.0,0.0 234.0,43.0Q204.0,86.0 185.0,138.0Q166.0,190.0 154.5,256.0Q143.0,322.0 136.0,406.0Q132.0,459.0 127.5,512.0Q123.0,565.0 113.0,596.0Q97.0,646.0 51.0,646.0Q29.0,646.0 7.0,636.0Q-15.0,626.0 -32.0,616.0Q-42.0,630.0 -51.0,645.5Q-60.0,661.0 -60.0,680.0Q-60.0,705.0 -42.5,717.0Q-25.0,729.0 2.0,729.0Q48.0,729.0 90.0,698.0Q132.0,667.0 158.0,620.0Q186.0,571.0 202.5,502.0Q219.0,433.0 227.0,356.0Q238.0,252.0 252.0,175.5Q266.0,99.0 305.0,50.0Q331.0,18.0 366.5,3.0Q402.0,-12.0 458.0,-12.0Q499.0,-12.0 530.5,-4.0Q562.0,4.0 592.0,21.0Q603.0,8.0 610.5,-9.5Q618.0,-27.0 618.0,-42.0Q618.0,-65.0 600.5,-79.0Q583.0,-93.0 555.5,-98.5Q528.0,-104.0 496.0,-104.0ZM258.0,54.0L229.0,166.0Q290.0,191.0 328.5,227.0Q367.0,263.0 385.5,300.0Q404.0,337.0 404.0,365.0Q404.0,394.0 385.0,414.0Q366.0,434.0 328.0,450.0L330.0,601.0L342.0,604.0Q393.0,547.0 426.0,478.5Q459.0,410.0 459.0,335.0Q459.0,291.0 442.5,243.0Q426.0,195.0 383.0,147.5Q340.0,100.0 258.0,54.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g35"/> </g> <g transform="translate(760,0)"> <use href="#g3"/> </g> <g transform="translate(1020,0)"> <use href="#g32"/> </g> <g transform="translate(1701,0)"> <use href="#g3"/> </g> <g transform="translate(1704,31)"> <use href="#g316"/> </g> <g transform="translate(1701,0)"> <use href="#g235"/> </g> </svg></p>
</li>
<li>
<p>Shaping did not match: 𑈙𑈯𑈧𑈵𑈥 (Don't delete JA/TA/LA before YA)</p>
<pre><code>Expected: None
Got     : ta_uMatrakhoj=0+704|lakhoj=2+636|yakarkhoj=2+663
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -447 2003 1856" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g149" d="M352.0,-159.0Q290.0,-159.0 232.5,-133.0Q175.0,-107.0 127.5,-64.5Q80.0,-22.0 47.0,27.0L53.0,82.0L60.0,84.0Q110.0,13.0 176.5,-32.0Q243.0,-77.0 316.0,-77.0Q381.0,-77.0 429.5,-42.0Q478.0,-7.0 510.0,51.5Q542.0,110.0 558.0,182.0Q574.0,254.0 574.0,327.0Q574.0,366.0 567.5,400.0Q561.0,434.0 547.0,455.0Q533.0,476.0 508.0,476.0Q480.0,476.0 451.0,451.5Q422.0,427.0 395.5,388.5Q369.0,350.0 347.5,305.5Q326.0,261.0 312.0,220.0L323.0,266.0Q325.0,245.0 326.0,224.0Q327.0,203.0 327.0,183.0Q327.0,134.0 317.0,99.0Q307.0,64.0 282.0,64.0Q265.0,64.0 245.0,74.5Q225.0,85.0 211.5,102.5Q198.0,120.0 198.0,141.0Q198.0,183.0 215.5,235.5Q233.0,288.0 259.0,339.5Q285.0,391.0 312.0,431.0Q345.0,480.0 385.5,515.5Q426.0,551.0 476.0,551.0Q528.0,551.0 564.0,515.0Q600.0,479.0 619.5,414.0Q639.0,349.0 639.0,261.0Q639.0,183.0 621.5,108.0Q604.0,33.0 568.0,-27.0Q532.0,-87.0 478.0,-123.0Q424.0,-159.0 352.0,-159.0ZM254.0,238.0Q236.0,311.0 221.0,353.0Q206.0,395.0 192.5,415.0Q179.0,435.0 166.0,441.0Q153.0,447.0 138.0,447.0Q119.0,447.0 98.0,440.5Q77.0,434.0 61.0,425.0Q51.0,439.0 43.0,456.0Q35.0,473.0 35.0,489.0Q35.0,510.0 55.0,524.0Q75.0,538.0 106.0,538.0Q140.0,538.0 170.0,517.5Q200.0,497.0 228.0,441.0Q256.0,385.0 283.0,278.0L254.0,238.0Z"/> <path id="g239" d="M214.0,224.0L88.0,279.0L88.0,293.0Q135.0,315.0 170.0,342.0Q205.0,369.0 225.0,398.0Q245.0,427.0 245.0,455.0Q245.0,481.0 227.5,496.0Q210.0,511.0 181.0,511.0Q152.0,511.0 114.5,496.5Q77.0,482.0 40.0,448.0Q23.0,464.0 11.5,480.5Q0.0,497.0 0.0,514.0Q0.0,537.0 19.0,552.0Q38.0,567.0 66.5,574.0Q95.0,581.0 123.0,581.0Q173.0,581.0 217.0,560.5Q261.0,540.0 288.5,504.0Q316.0,468.0 316.0,421.0Q316.0,384.0 295.0,344.5Q274.0,305.0 227.0,270.0L206.0,294.0L499.0,294.0L490.0,224.0L214.0,224.0ZM493.0,-9.0Q486.0,-2.0 473.0,17.5Q460.0,37.0 449.5,57.0Q439.0,77.0 437.0,83.0Q453.0,144.0 461.0,209.5Q469.0,275.0 469.0,340.0Q469.0,408.0 460.5,472.5Q452.0,537.0 437.0,600.0L513.0,600.0Q531.0,536.0 541.0,454.5Q551.0,373.0 551.0,293.0Q551.0,217.0 542.5,140.0Q534.0,63.0 517.0,0.0L493.0,-9.0Z"/> <path id="g310" d="M519.0,-9.0Q514.0,-4.0 504.0,9.5Q494.0,23.0 483.5,38.5Q473.0,54.0 465.5,67.5Q458.0,81.0 457.0,86.0Q472.0,127.0 485.5,169.0Q499.0,211.0 509.0,252.5Q519.0,294.0 524.5,332.0Q530.0,370.0 530.0,403.0Q530.0,457.0 513.0,483.0Q496.0,509.0 455.0,509.0Q427.0,509.0 391.0,498.0Q381.0,507.0 369.0,519.0Q357.0,531.0 345.5,544.5Q334.0,558.0 326.0,569.0L327.0,575.0Q344.0,585.0 369.0,592.5Q394.0,600.0 416.0,600.0Q462.0,600.0 503.5,567.5Q545.0,535.0 571.5,476.5Q598.0,418.0 598.0,339.0Q598.0,305.0 593.5,260.5Q589.0,216.0 581.0,168.0Q573.0,120.0 563.5,76.0Q554.0,32.0 544.0,0.0L519.0,-9.0ZM217.0,122.0Q177.0,122.0 141.0,140.0Q105.0,158.0 78.0,187.5Q51.0,217.0 35.5,254.0Q20.0,291.0 20.0,328.0Q20.0,374.0 42.5,413.0Q65.0,452.0 103.5,475.5Q142.0,499.0 189.0,499.0Q228.0,499.0 262.5,482.5Q297.0,466.0 323.5,438.0Q350.0,410.0 365.0,374.0Q380.0,338.0 380.0,299.0Q380.0,253.0 359.0,212.5Q338.0,172.0 301.5,147.0Q265.0,122.0 217.0,122.0ZM183.0,200.0Q217.0,200.0 244.5,218.5Q272.0,237.0 288.0,266.5Q304.0,296.0 304.0,330.0Q304.0,368.0 284.0,393.5Q264.0,419.0 224.0,419.0Q196.0,419.0 167.0,404.0Q138.0,389.0 119.0,360.5Q100.0,332.0 100.0,291.0Q100.0,248.0 122.5,224.0Q145.0,200.0 183.0,200.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g149"/> </g> <g transform="translate(704,0)"> <use href="#g239"/> </g> <g transform="translate(1340,0)"> <use href="#g310"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- Anusvarakhoj

- Nuktakhoj

- Shaddakhoj

- Sukunkhoj

- acutecomb

- aiMatrakhoj

- eMatrakhoj

- gravecomb

- halantkhoj

- rVocalicMatrakhoj

- tildecomb

- uMatrakhoj

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0326

- uni0327

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+11235</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 5 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 558:
multiply, plus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NullMark

- dblsectionmark.alt

- sectionmark.alt

- sha_eMatrakhoj

- sha_iMatrakhoj

- sha_iiMatrakhoj

- sha_uMatrakhoj

- shakhoj

- sixkhoj.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifKhojki/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, syriac, tai-le, math, tifinagh, malayalam, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2010 HYPHEN: try adding one of: coptic, kayah-li, lisu, arabic, yi, cham, armenian, sundanese, sora-sompeng, hebrew, kharoshthi, kaithi, syloti-nagri</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>khojki</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Sar (Latn, 500,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Nzakara (Latn, 50,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Cicipu (Latn, 44,000 speakers), South Central Banda (Latn, 244,000 speakers), Mango (Latn, 77,000 speakers), Vute (Latn, 21,000 speakers), Lugbara (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Yala (Latn, 200,000 speakers), Ebira (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Zapotec (Latn, 490,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Bafut (Latn, 158,146 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 1 | 0 | 3 | 9 | 96 | 7 | 135 | 0 | 
| 0% | 0% | 1% | 4% | 38% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
