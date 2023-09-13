## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[16] NotoSansNandinagari-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* BaBa.Nnagari
	* BaBa.Nnagari.ss03
	* BaBaRa.Nnagari.ss03
	* BaBha.Nnagari.ss03
	* BaDhaVa.Nnagari.ss02
	* BaGa.Nnagari
	* BaGa.Nnagari.ss03
	* BaGaRa.Nnagari
	* BaGaRa.Nnagari.ss03
	* BaLa.Nnagari and 158 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Nandinagari' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
DoubleAnusvaraAntargomukha.Nnagari [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- DdhaVirama.Nnagari.ss01

	- DhaVirama.Nnagari.ss01

	- HaVirama.Nnagari.ss01

	- NULL

	- NyaVirama.Nnagari

	- PhaVirama.Nnagari.ss01

	- TthaVirama.Nnagari.ss01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Dda.Nnagari (U+119BA): L<<371.0,559.0>--<60.0,558.0>>

	* VowelO.Nnagari (U+119AC): L<<371.0,559.0>--<60.0,558.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 2 | 10 | 118 | 6 | 110 | 0 |
| 2% | 1% | 4% | 47% | 2% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
