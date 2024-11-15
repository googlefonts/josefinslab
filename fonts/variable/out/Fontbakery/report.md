## FontBakery report

fontbakery version: 0.13.0a3



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] JosefinSlab-Italic[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/metrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 883, but got 750 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>

<details><summary>[1] JosefinSlab[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/metrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 883, but got 750 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[27] JosefinSlab-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> STAT table has Axis Value tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.stat.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>STAT table has no Axis Value tables.</p>
 [code: no-axis-value-tables]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure smart dropout control is enabled in "prep" table instructions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the <code>gftools fix-nonhinting</code> script.</p>
 [code: lacks-smart-dropout]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check name ID 25 to end with "Italic" for Italic VFs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.metadata.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name ID 25 must end with &quot;Italic&quot; for Italic fonts.</p>
 [code: nameid25-missing-italic]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table strings must not contain the string 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table entry contains &quot;Reserved Font Name&quot;:
&quot;Copyright 2020 The Josefin Slab Project Authors (<a href="https://github.com/googlefonts/josefinslab/">https://github.com/googlefonts/josefinslab/</a>), with Reserved Font Name Josefin.&quot;</p>
<p>This is an error except in a few specific rare cases.</p>
 [code: rfn]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at <a href="https://pypi.org/project/gftools/">https://pypi.org/project/gftools/</a></p>
 [code: lacks-gasp]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 110 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.axisregistry.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>STAT table is missing Axis Value Records</p>
 [code: missing-axis-values]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check hhea.caretSlopeRise and hhea.caretSlopeRun <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.hhea.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>hhea.caretSlopeRise and hhea.caretSlopeRun do not match with post.italicAngle.
Got: caretSlopeRise 1 and caretSlopeRun 0
Expected: caretSlopeRise 1000 and caretSlopeRun 213</p>
 [code: caretslope-mismatch]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 start point differs in glyph 'section' between location wght=100 and location wght=700

- Contour 0 in glyph 'section': becomes underweight between wght=100 and wght=700.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 543 among a set of 1 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 680:
less</p>
<p>Width = 708:
equal</p>
<p>Width = 650:
greater</p>
<p>Width = 559:
logicalnot</p>
<p>Width = 524:
plusminus</p>
<p>Width = 500:
multiply</p>
<p>Width = 501:
divide</p>
<p>Width = 523:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at . does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check OFL body text is correct. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The OFL.txt body text is incorrect. Please use <a href="https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt">https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt</a> as a template. You should only modify the first line.</p>
<p>Lines changed:</p>
<p>+ Copyright (c) 2010, Santiago Orozco (<a href="mailto:hi@typemade.mx">hi@typemade.mx</a>), with Reserved Font Name Josefin.\n</p>
 [code: incorrect-ofl-body-text]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13]</p>
 [code: http-in-description]



* ⚠️ **WARN** <p>Please consider updating the url from '<a href="https://scripts.sil.org/OFL">https://scripts.sil.org/OFL</a>' to '<a href="https://openfontlicense.org">https://openfontlicense.org</a>'.</p>
 [code: old-url]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> License URL matches License text on name table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13]</p>
 [code: http-in-description]



* ⚠️ **WARN** <p>Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13]</p>
 [code: http-in-description]



* ⚠️ **WARN** <p>Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13]</p>
 [code: http-in-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* J (U+004A): X=152.5,Y=2.0 (should be at baseline 0?)

* N (U+004E): X=716.0,Y=2.0 (should be at baseline 0?)

* S (U+0053): X=373.0,Y=702.0 (should be at cap-height 700?)

* a (U+0061): X=340.5,Y=374.0 (should be at x-height 375?)

* e (U+0065): X=339.5,Y=373.0 (should be at x-height 375?)

* g (U+0067): X=344.5,Y=374.0 (should be at x-height 375?)

* r (U+0072): X=289.5,Y=373.5 (should be at x-height 375?)

* s (U+0073): X=87.5,Y=0.5 (should be at baseline 0?)

* s (U+0073): X=202.5,Y=2.0 (should be at baseline 0?)

* s (U+0073): X=243.0,Y=376.0 (should be at x-height 375?)

* 18 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* A (U+0041) has a counter-clockwise outer contour

* AE (U+00C6) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* 292 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value ' GOO' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/superfamily.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>.</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/namecheck.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>The family name &quot;JosefinSlab&quot; seems to be already in use.
Please visit <a href="http://namecheck.fontdata.com">http://namecheck.fontdata.com</a> for more info.</p>
 [code: name-collision]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Hinting filesize impact:</p>
<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">JosefinSlab-Italic[wght].ttf</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Dehinted Size</td>
<td align="right">49.1kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">49.0kb</td>
</tr>
<tr>
<td align="left">Increase</td>
<td align="right">-24 bytes</td>
</tr>
<tr>
<td align="left">Change</td>
<td align="right">-0.0 %</td>
</tr>
</tbody>
</table>
 [code: size-impact]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/tables.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font contains the following optional tables:</p>
<pre><code>- loca

- GPOS
</code></pre>
 [code: optional-tables]





</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.description.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> EPAR table present in font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>EPAR table not present in font. To learn more see <a href="https://github.com/fonttools/fontbakery/issues/818">https://github.com/fonttools/fontbakery/issues/818</a></p>
 [code: lacks-EPAR]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 2.100']</p>
 [code: version-not-detected]



</div>
</details>
</div>
</details>

<details><summary>[2] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure VFs have 'ital' STAT axis. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.stat.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font JosefinSlab[wght].ttf is missing an 'ital' axis.</p>
 [code: missing-ital-axis]



* 🔥 **FAIL** <p>Font JosefinSlab-Italic[wght].ttf is missing an 'ital' axis.</p>
 [code: missing-ital-axis]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.stat.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>None of the fonts lack a STAT table.</p>
<pre><code>And these are the most common STAT axis orderings:
('wght', 2)
</code></pre>
 [code: summary]



</div>
</details>
</div>
</details>

<details><summary>[23] JosefinSlab[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> STAT table has Axis Value tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.stat.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>STAT table has no Axis Value tables.</p>
 [code: no-axis-value-tables]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure smart dropout control is enabled in "prep" table instructions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the <code>gftools fix-nonhinting</code> script.</p>
 [code: lacks-smart-dropout]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure component transforms do not perform scaling or rotation. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had components with scaling or rotation
or inverted outline direction:</p>
<ul>
<li>exclamdown (component exclam)</li>
<li>guillemotright (component guillemotleft)</li>
<li>guilsinglright (component guilsinglleft)</li>
</ul>
 [code: transformed-components]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table strings must not contain the string 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table entry contains &quot;Reserved Font Name&quot;:
&quot;Copyright 2020 The Josefin Slab Project Authors (<a href="https://github.com/googlefonts/josefinslab/">https://github.com/googlefonts/josefinslab/</a>), with Reserved Font Name Josefin.&quot;</p>
<p>This is an error except in a few specific rare cases.</p>
 [code: rfn]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at <a href="https://pypi.org/project/gftools/">https://pypi.org/project/gftools/</a></p>
 [code: lacks-gasp]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 110 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.axisregistry.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>STAT table is missing Axis Value Records</p>
 [code: missing-axis-values]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 start point differs in glyph 'at' between location wght=100 and location wght=700

- Contour 0 in glyph 'at': becomes underweight between wght=100 and wght=700.

- Contour 0 start point differs in glyph 'section' between location wght=100 and location wght=700

- Contour 0 in glyph 'section': becomes underweight between wght=100 and wght=700.

- Contour 0 start point differs in glyph 'eight' between location wght=100 and location wght=700

- Contour 0 in glyph 'eight': becomes underweight between wght=100 and wght=700.

- Contour 0 start point differs in glyph 'percent' between location wght=100 and location wght=700

- Contour 2 start point differs in glyph 'percent' between location wght=100 and location wght=700
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 524 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 543:
plus</p>
<p>Width = 680:
less</p>
<p>Width = 708:
equal</p>
<p>Width = 650:
greater</p>
<p>Width = 559:
logicalnot</p>
<p>Width = 500:
multiply</p>
<p>Width = 501:
divide</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at . does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check OFL body text is correct. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The OFL.txt body text is incorrect. Please use <a href="https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt">https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt</a> as a template. You should only modify the first line.</p>
<p>Lines changed:</p>
<p>+ Copyright (c) 2010, Santiago Orozco (<a href="mailto:hi@typemade.mx">hi@typemade.mx</a>), with Reserved Font Name Josefin.\n</p>
 [code: incorrect-ofl-body-text]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Atilde (U+00C3): X=474.0,Y=752.0 (should be at ascender 750?)

* J (U+004A): X=193.0,Y=2.0 (should be at baseline 0?)

* N (U+004E): X=712.0,Y=2.0 (should be at baseline 0?)

* Ntilde (U+00D1): X=712.0,Y=2.0 (should be at baseline 0?)

* Ntilde (U+00D1): X=472.0,Y=752.0 (should be at ascender 750?)

* Otilde (U+00D5): X=459.0,Y=752.0 (should be at ascender 750?)

* OE (U+0152): X=845.0,Y=701.0 (should be at cap-height 700?)

* S (U+0053): X=297.5,Y=702.0 (should be at cap-height 700?)

* b (U+0062): X=243.5,Y=374.0 (should be at x-height 375?)

* d (U+0064): X=288.5,Y=374.0 (should be at x-height 375?)

* 18 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* A (U+0041) has a counter-clockwise outer contour

* AE (U+00C6) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* 288 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/superfamily.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>.</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/namecheck.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>The family name &quot;JosefinSlab&quot; seems to be already in use.
Please visit <a href="http://namecheck.fontdata.com">http://namecheck.fontdata.com</a> for more info.</p>
 [code: name-collision]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Hinting filesize impact:</p>
<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">JosefinSlab[wght].ttf</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Dehinted Size</td>
<td align="right">46.9kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">46.9kb</td>
</tr>
<tr>
<td align="left">Increase</td>
<td align="right">-24 bytes</td>
</tr>
<tr>
<td align="left">Change</td>
<td align="right">-0.0 %</td>
</tr>
</tbody>
</table>
 [code: size-impact]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/tables.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font contains the following optional tables:</p>
<pre><code>- loca

- GPOS
</code></pre>
 [code: optional-tables]





</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.description.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> EPAR table present in font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>EPAR table not present in font. To learn more see <a href="https://github.com/fonttools/fontbakery/issues/818">https://github.com/fonttools/fontbakery/issues/818</a></p>
 [code: lacks-EPAR]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 2.100']</p>
 [code: version-not-detected]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 19 | 20 | 203 | 15 | 231 | 0 | 
| 0% | 0% | 4% | 4% | 42% | 3% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* PASS
* DEBUG
