## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansNandinagari-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 944, but got 900 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[11] NotoSansNandinagari-Regular.ttf</summary>
<div>
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
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- DdhaVirama.Nnagari.ss01

- DhaVirama.Nnagari.ss01

- HaVirama.Nnagari.ss01

- NULL

- NyaVirama.Nnagari

- PhaVirama.Nnagari.ss01

- TthaVirama.Nnagari.ss01
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
DoubleAnusvaraAntargomukha.Nnagari</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansNandinagari/googlefonts/ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, hebrew, duployan, tifinagh, todhri, tai-le, malayalam, old-permic, coptic, math, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, bhaiksuki, chakma, duployan, kayah-li, khojki, buhid, cham, khudawadi, new-tai-lue, lepcha, batak, tai-le, tagalog, gunjala-gondi, mandaic, telugu, tagbanwa, limbu, myanmar, hebrew, brahmi, saurashtra, tai-viet, balinese, dogra, phags-pa, kannada, kharoshthi, thai, zanabazar-square, hatran, nko, yi, kaithi, oriya, syriac, buginese, syloti-nagri, hanunoo, gujarati, grantha, arabic, khmer, malayalam, sundanese, warang-citi, tifinagh, mongolian, psalter-pahlavi, modi, siddham, takri, tibetan, hanifi-rohingya, javanese, bengali, devanagari, avestan, newa, thaana, meetei-mayek, lao, masaram-gondi, manichaean, tai-tham, sogdian, pahawh-hmong, mahajani, gurmukhi, tamil, tirhuta, sharada, rejang</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: sinhala, bhaiksuki, chakma, duployan, kayah-li, khojki, buhid, cham, khudawadi, new-tai-lue, lepcha, batak, tai-le, tagalog, gunjala-gondi, mandaic, telugu, tagbanwa, limbu, myanmar, hebrew, brahmi, saurashtra, tai-viet, balinese, dogra, phags-pa, kannada, kharoshthi, thai, zanabazar-square, nko, yi, kaithi, oriya, syriac, buginese, syloti-nagri, hanunoo, gujarati, grantha, arabic, khmer, malayalam, sundanese, warang-citi, tifinagh, mongolian, psalter-pahlavi, modi, siddham, takri, tibetan, hanifi-rohingya, javanese, bengali, devanagari, avestan, newa, thaana, meetei-mayek, lao, masaram-gondi, manichaean, tai-tham, sogdian, old-hungarian, pahawh-hmong, mahajani, gurmukhi, tamil, tirhuta, sharada, rejang</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: bhaiksuki, chakma, khudawadi, caucasian-albanian, gunjala-gondi, saurashtra, balinese, yi, hanunoo, gujarati, tibetan, hanifi-rohingya, devanagari, masaram-gondi, mahajani, tirhuta, tai-le, cham, ahom, adlam, tagbanwa, limbu, tai-viet, armenian, zanabazar-square, math, kaithi, oriya, syriac, syloti-nagri, sundanese, psalter-pahlavi, bengali, meetei-mayek, manichaean, sogdian, music, tamil, wancho, mende-kikakui, rejang, sinhala, new-tai-lue, tagalog, buhid, lepcha, batak, mandaic, telugu, myanmar, kharoshthi, nko, canadian-aboriginal, osage, warang-citi, malayalam, miao, bassa-vah, modi, siddham, javanese, newa, thaana, old-permic, gurmukhi, takri, duployan, pahawh-hmong, khojki, kayah-li, tifinagh, symbols, hebrew, brahmi, phags-pa, dogra, kannada, thai, buginese, grantha, khmer, marchen, mongolian, soyombo, lao, tai-tham, coptic, sharada, elbasan</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>nandinagari</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), South Central Banda (Latn, 244,000 speakers), Ma’di (Latn, 584,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Sar (Latn, 500,000 speakers), Cicipu (Latn, 44,000 speakers), Koonzime (Latn, 40,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Mfumte (Latn, 79,000 speakers), Gulay (Latn, 250,478 speakers), Ebira (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Ekpeye (Latn, 226,000 speakers), Aghem (Latn, 38,843 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Avokaya (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Bafut (Latn, 158,146 speakers), Zapotec (Latn, 490,000 speakers), Fur (Latn, 1,230,163 speakers), Basaa (Latn, 332,940 speakers), Vute (Latn, 21,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* GaDha.Nnagari.ss02: L&lt;&lt;574.0,-243.0&gt;--&lt;574.0,-243.0&gt;&gt; -&gt; L&lt;&lt;574.0,-243.0&gt;--&lt;574.0,-243.0&gt;&gt;

* KaTaRa.Nnagari.ss03: L&lt;&lt;390.0,-187.0&gt;--&lt;390.0,-187.0&gt;&gt; -&gt; L&lt;&lt;390.0,-187.0&gt;--&lt;390.0,-187.0&gt;&gt;

* MaRa.Nnagari: L&lt;&lt;313.0,406.0&gt;--&lt;320.0,406.0&gt;&gt; -&gt; L&lt;&lt;320.0,406.0&gt;--&lt;492.0,406.0&gt;&gt;

* MaRa.Nnagari: L&lt;&lt;492.0,335.0&gt;--&lt;320.0,335.0&gt;&gt; -&gt; L&lt;&lt;320.0,335.0&gt;--&lt;317.0,335.0&gt;&gt;

* MatraAa1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt; -&gt; L&lt;&lt;104.0,622.0&gt;--&lt;154.0,622.0&gt;&gt;

* MatraAaReph1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt; -&gt; L&lt;&lt;104.0,622.0&gt;--&lt;154.0,622.0&gt;&gt;

* MatraAu1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt; -&gt; L&lt;&lt;104.0,622.0&gt;--&lt;154.0,622.0&gt;&gt;

* MatraAuReph1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt; -&gt; L&lt;&lt;104.0,622.0&gt;--&lt;154.0,622.0&gt;&gt;

* MatraO1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt; -&gt; L&lt;&lt;104.0,622.0&gt;--&lt;154.0,622.0&gt;&gt;

* MatraOReph1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt; -&gt; L&lt;&lt;104.0,622.0&gt;--&lt;154.0,622.0&gt;&gt;

* ThaHalf.Nnagari: L&lt;&lt;213.0,622.0&gt;--&lt;213.0,622.0&gt;&gt; -&gt; L&lt;&lt;213.0,622.0&gt;--&lt;852.0,622.0&gt;&gt;

* VowelAa.Nnagari.ss03: L&lt;&lt;519.0,623.0&gt;--&lt;887.0,622.0&gt;&gt; -&gt; L&lt;&lt;887.0,622.0&gt;--&lt;937.0,622.0&gt;&gt;

* VowelAu.Nnagari.ss03: L&lt;&lt;519.0,623.0&gt;--&lt;887.0,622.0&gt;&gt; -&gt; L&lt;&lt;887.0,622.0&gt;--&lt;937.0,622.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* TaMa.Nnagari.ss01: B&lt;&lt;432.0,330.5&gt;-&lt;431.0,373.0&gt;-&lt;430.0,415.0&gt;&gt;/L&lt;&lt;430.0,415.0&gt;--&lt;430.0,375.0&gt;&gt; = 1.3639275316029233
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* Dda.Nnagari (U+119BA): L&lt;&lt;371.0,559.0&gt;--&lt;60.0,558.0&gt;&gt;

* DdaVirama.Nnagari: L&lt;&lt;371.0,559.0&gt;--&lt;60.0,558.0&gt;&gt;

* JaNyaVa.Nnagari: L&lt;&lt;827.0,334.0&gt;--&lt;826.0,-201.0&gt;&gt;

* MatraAa1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt;

* MatraAa1.Nnagari: L&lt;&lt;76.0,558.0&gt;--&lt;-179.0,559.0&gt;&gt;

* MatraAaReph1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt;

* MatraAaReph1.Nnagari: L&lt;&lt;76.0,558.0&gt;--&lt;-179.0,559.0&gt;&gt;

* MatraAu1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt;

* MatraAu1.Nnagari: L&lt;&lt;76.0,558.0&gt;--&lt;-179.0,559.0&gt;&gt;

* MatraAuReph1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt;

* MatraAuReph1.Nnagari: L&lt;&lt;76.0,558.0&gt;--&lt;-179.0,559.0&gt;&gt;

* MatraO1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt;

* MatraO1.Nnagari: L&lt;&lt;76.0,558.0&gt;--&lt;-179.0,559.0&gt;&gt;

* MatraOReph1.Nnagari: L&lt;&lt;-264.0,623.0&gt;--&lt;104.0,622.0&gt;&gt;

* MatraOReph1.Nnagari: L&lt;&lt;76.0,558.0&gt;--&lt;-179.0,559.0&gt;&gt;

* VowelAa.Nnagari.ss03: L&lt;&lt;519.0,623.0&gt;--&lt;887.0,622.0&gt;&gt;

* VowelAa.Nnagari.ss03: L&lt;&lt;859.0,558.0&gt;--&lt;604.0,559.0&gt;&gt;

* VowelAu.Nnagari.ss03: L&lt;&lt;519.0,623.0&gt;--&lt;887.0,622.0&gt;&gt;

* VowelAu.Nnagari.ss03: L&lt;&lt;859.0,558.0&gt;--&lt;604.0,559.0&gt;&gt;

* VowelO.Nnagari (U+119AC): L&lt;&lt;371.0,559.0&gt;--&lt;60.0,558.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
| 0 | 0 | 2 | 10 | 116 | 6 | 117 | 0 | 
| 0% | 0% | 1% | 4% | 46% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
