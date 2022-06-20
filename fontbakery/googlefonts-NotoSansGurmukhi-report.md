## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Gurmukhi Regular: 896
Noto Sans Gurmukhi Black: 896
Noto Sans Gurmukhi Bold: 896
Noto Sans Gurmukhi ExtraBold: 896
Noto Sans Gurmukhi ExtraLight: 896
Noto Sans Gurmukhi Light: 896
Noto Sans Gurmukhi Medium: 896
Noto Sans Gurmukhi SemiBold: 896
Noto Sans Gurmukhi Thin: 896
Noto Sans Gurmukhi UI Black: 1069
Noto Sans Gurmukhi UI Bold: 1069
Noto Sans Gurmukhi UI ExtraBold: 1069
Noto Sans Gurmukhi UI ExtraLight: 1069
Noto Sans Gurmukhi UI Light: 1069
Noto Sans Gurmukhi UI Medium: 1069
Noto Sans Gurmukhi UI Regular: 1069
Noto Sans Gurmukhi UI SemiBold: 1069
Noto Sans Gurmukhi UI Thin: 1069 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Noto Sans Gurmukhi Regular: -408
Noto Sans Gurmukhi Black: -408
Noto Sans Gurmukhi Bold: -408
Noto Sans Gurmukhi ExtraBold: -408
Noto Sans Gurmukhi ExtraLight: -408
Noto Sans Gurmukhi Light: -408
Noto Sans Gurmukhi Medium: -408
Noto Sans Gurmukhi SemiBold: -408
Noto Sans Gurmukhi Thin: -408
Noto Sans Gurmukhi UI Black: -293
Noto Sans Gurmukhi UI Bold: -293
Noto Sans Gurmukhi UI ExtraBold: -293
Noto Sans Gurmukhi UI ExtraLight: -293
Noto Sans Gurmukhi UI Light: -293
Noto Sans Gurmukhi UI Medium: -293
Noto Sans Gurmukhi UI Regular: -293
Noto Sans Gurmukhi UI SemiBold: -293
Noto Sans Gurmukhi UI Thin: -293 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Noto Sans Gurmukhi Regular: 896
Noto Sans Gurmukhi Black: 896
Noto Sans Gurmukhi Bold: 896
Noto Sans Gurmukhi ExtraBold: 896
Noto Sans Gurmukhi ExtraLight: 896
Noto Sans Gurmukhi Light: 896
Noto Sans Gurmukhi Medium: 896
Noto Sans Gurmukhi SemiBold: 896
Noto Sans Gurmukhi Thin: 896
Noto Sans Gurmukhi UI Black: 1069
Noto Sans Gurmukhi UI Bold: 1069
Noto Sans Gurmukhi UI ExtraBold: 1069
Noto Sans Gurmukhi UI ExtraLight: 1069
Noto Sans Gurmukhi UI Light: 1069
Noto Sans Gurmukhi UI Medium: 1069
Noto Sans Gurmukhi UI Regular: 1069
Noto Sans Gurmukhi UI SemiBold: 1069
Noto Sans Gurmukhi UI Thin: 1069 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Noto Sans Gurmukhi Regular: 408
Noto Sans Gurmukhi Black: 408
Noto Sans Gurmukhi Bold: 408
Noto Sans Gurmukhi ExtraBold: 408
Noto Sans Gurmukhi ExtraLight: 408
Noto Sans Gurmukhi Light: 408
Noto Sans Gurmukhi Medium: 408
Noto Sans Gurmukhi SemiBold: 408
Noto Sans Gurmukhi Thin: 408
Noto Sans Gurmukhi UI Black: 293
Noto Sans Gurmukhi UI Bold: 293
Noto Sans Gurmukhi UI ExtraBold: 293
Noto Sans Gurmukhi UI ExtraLight: 293
Noto Sans Gurmukhi UI Light: 293
Noto Sans Gurmukhi UI Medium: 293
Noto Sans Gurmukhi UI Regular: 293
Noto Sans Gurmukhi UI SemiBold: 293
Noto Sans Gurmukhi UI Thin: 293 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Noto Sans Gurmukhi Regular: 896
Noto Sans Gurmukhi Black: 896
Noto Sans Gurmukhi Bold: 896
Noto Sans Gurmukhi ExtraBold: 896
Noto Sans Gurmukhi ExtraLight: 896
Noto Sans Gurmukhi Light: 896
Noto Sans Gurmukhi Medium: 896
Noto Sans Gurmukhi SemiBold: 896
Noto Sans Gurmukhi Thin: 896
Noto Sans Gurmukhi UI Black: 1069
Noto Sans Gurmukhi UI Bold: 1069
Noto Sans Gurmukhi UI ExtraBold: 1069
Noto Sans Gurmukhi UI ExtraLight: 1069
Noto Sans Gurmukhi UI Light: 1069
Noto Sans Gurmukhi UI Medium: 1069
Noto Sans Gurmukhi UI Regular: 1069
Noto Sans Gurmukhi UI SemiBold: 1069
Noto Sans Gurmukhi UI Thin: 1069 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Noto Sans Gurmukhi Regular: -408
Noto Sans Gurmukhi Black: -408
Noto Sans Gurmukhi Bold: -408
Noto Sans Gurmukhi ExtraBold: -408
Noto Sans Gurmukhi ExtraLight: -408
Noto Sans Gurmukhi Light: -408
Noto Sans Gurmukhi Medium: -408
Noto Sans Gurmukhi SemiBold: -408
Noto Sans Gurmukhi Thin: -408
Noto Sans Gurmukhi UI Black: -293
Noto Sans Gurmukhi UI Bold: -293
Noto Sans Gurmukhi UI ExtraBold: -293
Noto Sans Gurmukhi UI ExtraLight: -293
Noto Sans Gurmukhi UI Light: -293
Noto Sans Gurmukhi UI Medium: -293
Noto Sans Gurmukhi UI Regular: -293
Noto Sans Gurmukhi UI SemiBold: -293
Noto Sans Gurmukhi UI Thin: -293 [code: descent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[18] NotoSansGurmukhi[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansGurmukhi[wght].ttf' must be renamed to 'NotoSansGurmukhi[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Check variable font instances don't have duplicate names (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont_duplicate_instance_names">com.google.fonts/check/varfont_duplicate_instance_names</a>)</summary><div>


* 🔥 **FAIL** Following instances names are duplicate: 
	- ExtraLight
	- Light
	- Regular
	- Medium
	- SemiBold
	- Bold
 [code: duplicate-instance-names]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 270. [code: invalid-default-instance-postscript-nameid:270]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 279. [code: invalid-default-instance-postscript-nameid:279]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- udaatuuUIguru

	- numbersign

	- semicolon

	- vasubscript1UIguru

	- parenleft

	- raUIguru

	- hasubscripthalantUIguru

	- quotedbl

	- four

	- greater 

	- And 68 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* caguru
	* aaguru
	* nyanuktaprehalfguru
	* aubindiguru
	* lanuktaprehalfguru
	* thaguru
	* auguru
	* banuktaguru
	* ddhaprehalfguru
	* bhaguru and 109 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 623 but it should be 642 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* braceleft.guru (U+007B): X=159.0,Y=2.0 (should be at baseline 0?)

	* uni0951 (U+0951): X=-217.0,Y=895.0 (should be at ascender 896?)

	* uni0951 (U+0951): X=-99.0,Y=895.0 (should be at ascender 896?)

	* eeguru (U+0A0F): X=198.0,Y=894.0 (should be at ascender 896?)

	* eeguru (U+0A0F): X=220.0,Y=895.5 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-442.0,Y=894.0 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-420.0,Y=895.5 (should be at ascender 896?)

	* oneguru (U+0A67): X=440.5,Y=2.0 (should be at baseline 0?)

	* threeguru (U+0A69): X=153.0,Y=621.0 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=454.0,Y=-0.5 (should be at baseline 0?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<274.0,163.0>--<274.0,158.0>>

	* iiguru (U+0A08) contains a short segment L<<706.0,622.0>--<706.0,635.0>>

	* chaguru (U+0A1B) contains a short segment B<<258.0,327.0>-<242.0,327.0>-<235.5,325.5>>

	* chaguru (U+0A1B) contains a short segment B<<235.5,325.5>-<229.0,324.0>-<226.0,322.0>>

	* chaguru (U+0A1B) contains a short segment B<<226.0,322.0>-<219.0,318.0>-<219.0,308.0>>

	* jaguru (U+0A1C) contains a short segment L<<88.0,221.0>--<84.0,221.0>>

	* nyaguru (U+0A1E) contains a short segment B<<125.0,189.0>-<117.0,192.0>-<109.0,195.0>>

	* nyaguru (U+0A1E) contains a short segment B<<221.5,325.5>-<215.0,324.0>-<212.0,322.0>>

	* nyaguru (U+0A1E) contains a short segment B<<212.0,322.0>-<205.0,318.0>-<205.0,308.0>>

	* nyaguru (U+0A1E) contains a short segment B<<205.0,308.0>-<205.0,298.0>-<214.0,293.0>> 

	* And 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nyanuktaprehalfguru
	* lanuktaprehalfguru
	* thaguru
	* auguru
	* banuktaguru
	* ddhaprehalfguru
	* bhaguru
	* khanuktaprehalfguru
	* nnaprehalfguru
	* vasubscriptuguru and 84 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 601 but it should be 617 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five.guru (U+0035): X=127.0,Y=-0.5 (should be at baseline 0?)

	* eeguru (U+0A0F): X=184.0,Y=894.0 (should be at ascender 896?)

	* eeguru (U+0A0F): X=200.5,Y=895.5 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-426.0,Y=894.0 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-409.5,Y=895.5 (should be at ascender 896?)

	* twoguru (U+0A68): X=136.5,Y=621.0 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=442.5,Y=1.0 (should be at baseline 0?)

	* eightguru (U+0A6E): X=497.0,Y=1.0 (should be at baseline 0?)

	* nineguru (U+0A6F): X=497.0,Y=1.0 (should be at baseline 0?)

	* uni262C (U+262C): X=343.0,Y=1.0 (should be at baseline 0?) 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<228.0,134.0>--<228.0,127.0>>

	* aaguru (U+0A06) contains a short segment B<<355.5,395.5>-<350.0,415.0>-<345.0,424.0>>

	* aiguru (U+0A10) contains a short segment B<<403.5,760.0>-<409.0,760.0>-<413.0,760.0>>

	* auguru (U+0A14) contains a short segment L<<578.0,867.0>--<578.0,867.0>>

	* ghaguru (U+0A18) contains a short segment B<<580.0,249.0>-<592.0,253.0>-<601.0,260.0>>

	* chaguru (U+0A1B) contains a short segment B<<221.5,349.5>-<210.0,348.0>-<202.0,343.0>>

	* jaguru (U+0A1C) contains a short segment L<<104.0,259.0>--<89.0,259.0>>

	* nyaguru (U+0A1E) contains a short segment B<<201.0,349.0>-<189.0,347.0>-<183.0,342.0>>

	* nyaguru (U+0A1E) contains a short segment B<<276.0,176.0>-<267.0,173.0>-<262.0,169.0>>

	* nyaguru (U+0A1E) contains a short segment B<<262.0,169.0>-<253.0,162.0>-<253.0,150.0>> 

	* And 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nyaguru (U+0A1E): L<<257.0,451.0>--<257.0,451.0>> -> L<<257.0,451.0>--<388.0,451.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi ExtraBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* caguru
	* aaguru
	* nyanuktaprehalfguru
	* aubindiguru
	* lanuktaprehalfguru
	* thaguru
	* auguru
	* banuktaguru
	* ddhaprehalfguru
	* bhaguru and 93 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 611 but it should be 629 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five.guru (U+0035): X=131.0,Y=-0.5 (should be at baseline 0?)

	* eeguru (U+0A0F): X=191.0,Y=894.0 (should be at ascender 896?)

	* eeguru (U+0A0F): X=209.5,Y=895.5 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-433.0,Y=894.0 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-414.5,Y=895.5 (should be at ascender 896?)

	* oneguru (U+0A67): X=443.0,Y=2.0 (should be at baseline 0?)

	* twoguru (U+0A68): X=138.0,Y=621.5 (should be at cap-height 622?)

	* threeguru (U+0A69): X=149.0,Y=620.5 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=447.5,Y=0.5 (should be at baseline 0?)

	* eightguru (U+0A6E): X=504.0,Y=1.5 (should be at baseline 0?) 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<249.0,147.0>--<249.0,141.0>>

	* iiguru (U+0A08) contains a short segment B<<538.0,680.0>-<539.0,670.0>-<540.0,662.0>>

	* chaguru (U+0A1B) contains a short segment B<<228.0,338.5>-<219.0,337.0>-<213.0,333.0>>

	* chaguru (U+0A1B) contains a short segment B<<213.0,333.0>-<202.0,327.0>-<202.0,313.0>>

	* jaguru (U+0A1C) contains a short segment L<<97.0,241.0>--<87.0,241.0>>

	* jhaguru (U+0A1D) contains a short segment B<<311.0,418.0>-<311.0,418.0>-<313.0,418.0>>

	* nyaguru (U+0A1E) contains a short segment B<<210.5,338.0>-<201.0,336.0>-<196.0,333.0>>

	* nyaguru (U+0A1E) contains a short segment B<<196.0,333.0>-<187.0,326.0>-<187.0,314.0>>

	* nyaguru (U+0A1E) contains a short segment B<<289.5,173.0>-<281.0,171.0>-<276.0,167.0>>

	* nyaguru (U+0A1E) contains a short segment B<<276.0,167.0>-<268.0,161.0>-<268.0,150.0>> 

	* And 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* banuktaguru
	* banuktaprehalfguru
	* baprehalfguru and baguru
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 535 but it should be 546 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.guru (U+0021): X=210.5,Y=1.5 (should be at baseline 0?)

	* exclam.guru (U+0021): X=158.5,Y=1.5 (should be at baseline 0?)

	* comma.guru (U+002C): X=80.0,Y=0.5 (should be at baseline 0?)

	* period.guru (U+002E): X=136.0,Y=1.5 (should be at baseline 0?)

	* period.guru (U+002E): X=84.5,Y=1.5 (should be at baseline 0?)

	* two.guru (U+0032): X=91.0,Y=623.0 (should be at cap-height 622?)

	* three.guru (U+0033): X=129.0,Y=-1.5 (should be at baseline 0?)

	* five.guru (U+0035): X=152.5,Y=1.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=105.0,Y=-2.0 (should be at baseline 0?)

	* colon.guru (U+003A): X=97.5,Y=1.5 (should be at baseline 0?) 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<102.0,39.0>--<102.0,37.0>>

	* uguru (U+0A09) contains a short segment L<<585.0,587.0>--<585.0,582.0>>

	* uuguru (U+0A0A) contains a short segment L<<585.0,587.0>--<585.0,582.0>>

	* aiguru (U+0A10) contains a short segment B<<350.0,855.0>-<345.0,855.0>-<341.0,855.0>>

	* aiguru (U+0A10) contains a short segment L<<595.0,613.0>--<597.0,611.0>>

	* ooguru (U+0A13) contains a short segment L<<585.0,587.0>--<585.0,584.0>>

	* jaguru (U+0A1C) contains a short segment L<<104.0,324.0>--<93.0,324.0>>

	* jaguru (U+0A1C) contains a short segment B<<120.0,424.0>-<134.0,424.0>-<138.5,412.5>>

	* ddhaguru (U+0A22) contains a short segment L<<93.0,352.0>--<81.0,352.0>>

	* ddhaguru (U+0A22) contains a short segment B<<49.5,357.5>-<38.0,363.0>-<38.0,376.0>> 

	* And 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* banuktaguru
	* uunuktaaddakguru
	* unuktaaddakguru
	* jhaprehalfguru
	* jhanuktaguru
	* uuaddakguru
	* banuktaprehalfguru
	* uaddakaltguru
	* jhanuktaprehalfguru
	* uaddakguru and 4 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 546 but it should be 558 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.guru (U+002C): X=78.0,Y=-0.5 (should be at baseline 0?)

	* three.guru (U+0033): X=129.0,Y=-1.5 (should be at baseline 0?)

	* five.guru (U+0035): X=148.5,Y=0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=103.0,Y=-1.0 (should be at baseline 0?)

	* semicolon.guru (U+003B): X=75.5,Y=-0.5 (should be at baseline 0?)

	* oneguru (U+0A67): X=317.0,Y=620.0 (should be at cap-height 622?)

	* eightguru (U+0A6E): X=460.5,Y=1.5 (should be at baseline 0?)

	* nineguru (U+0A6F): X=460.0,Y=1.5 (should be at baseline 0?)

	* ekonkarguru (U+0A74): X=311.0,Y=620.0 (should be at cap-height 622?)

	* uni262C (U+262C): X=343.0,Y=1.0 (should be at baseline 0?) 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<122.0,56.0>--<122.0,54.0>>

	* aaguru (U+0A06) contains a short segment B<<331.0,123.0>-<317.0,123.0>-<308.0,132.5>>

	* aaguru (U+0A06) contains a short segment B<<92.0,225.0>-<78.0,225.0>-<69.0,234.5>>

	* aiguru (U+0A10) contains a short segment B<<359.5,843.0>-<355.0,843.0>-<351.0,843.0>>

	* aiguru (U+0A10) contains a short segment B<<604.0,612.0>-<606.0,609.0>-<608.0,606.0>>

	* jaguru (U+0A1C) contains a short segment L<<105.0,312.0>--<91.0,312.0>>

	* ddhaguru (U+0A22) contains a short segment L<<96.0,340.0>--<82.0,340.0>>

	* daguru (U+0A26) contains a short segment L<<96.0,312.0>--<82.0,312.0>>

	* laguru (U+0A32) contains a short segment L<<408.0,50.0>--<419.0,50.0>>

	* laguru (U+0A32) contains a short segment L<<245.0,0.0>--<238.0,0.0>> 

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nyanuktaprehalfguru
	* lanuktaprehalfguru
	* thaguru
	* banuktaguru
	* bhaguru
	* khanuktaprehalfguru
	* ddanuktaprehalfguru
	* vasubscriptuuguru
	* oobindiguru
	* thaprehalfguru and 59 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 576 but it should be 589 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.guru (U+0033): X=127.0,Y=-1.0 (should be at baseline 0?)

	* five.guru (U+0035): X=138.0,Y=-0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=92.0,Y=-2.0 (should be at baseline 0?)

	* question.guru (U+003F): X=178.5,Y=620.5 (should be at cap-height 622?)

	* eeguru (U+0A0F): X=167.0,Y=895.0 (should be at ascender 896?)

	* eeguru (U+0A0F): X=182.0,Y=895.5 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-406.0,Y=895.0 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-391.0,Y=895.5 (should be at ascender 896?)

	* khanuktaguru (U+0A59): X=125.5,Y=0.5 (should be at baseline 0?)

	* khanuktaguru (U+0A59): X=215.0,Y=0.5 (should be at baseline 0?) 

	* And 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<177.0,99.0>--<177.0,95.0>>

	* auguru (U+0A14) contains a short segment B<<482.0,755.0>-<482.0,759.0>-<482.0,761.0>>

	* jaguru (U+0A1C) contains a short segment L<<105.0,282.0>--<88.0,282.0>>

	* jhaguru (U+0A1D) contains a short segment B<<298.0,413.0>-<300.0,413.0>-<301.0,413.0>>

	* ddhaguru (U+0A22) contains a short segment L<<101.0,314.0>--<84.0,314.0>>

	* daguru (U+0A26) contains a short segment L<<101.0,285.0>--<84.0,285.0>>

	* laguru (U+0A32) contains a short segment L<<421.0,85.0>--<432.0,85.0>>

	* laguru (U+0A32) contains a short segment L<<260.0,0.0>--<254.0,0.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<421.0,85.0>--<432.0,85.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<260.0,0.0>--<254.0,0.0>> 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhi-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nyanuktaprehalfguru
	* thaguru
	* banuktaguru
	* khanuktaprehalfguru
	* oobindiguru
	* thaprehalfguru
	* uunuktaaddakguru
	* unuktaaddakguru
	* ubindinuktaguru
	* fourguru and 31 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 565 but it should be 577 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.guru (U+0021): X=252.5,Y=2.0 (should be at baseline 0?)

	* exclam.guru (U+0021): X=165.0,Y=2.0 (should be at baseline 0?)

	* period.guru (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period.guru (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three.guru (U+0033): X=128.5,Y=-1.5 (should be at baseline 0?)

	* three.guru (U+0033): X=344.5,Y=620.5 (should be at cap-height 622?)

	* five.guru (U+0035): X=142.0,Y=-0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=98.0,Y=-1.0 (should be at baseline 0?)

	* nine.guru (U+0039): X=341.5,Y=621.5 (should be at cap-height 622?)

	* colon.guru (U+003A): X=103.0,Y=2.0 (should be at baseline 0?) 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<156.0,85.0>--<156.0,81.0>>

	* khaguru (U+0A16) contains a short segment B<<188.0,460.0>-<188.0,456.0>-<188.0,454.0>>

	* jaguru (U+0A1C) contains a short segment L<<106.0,291.0>--<88.0,291.0>>

	* ddhaguru (U+0A22) contains a short segment L<<101.0,320.0>--<83.0,320.0>>

	* daguru (U+0A26) contains a short segment L<<101.0,291.0>--<83.0,291.0>>

	* laguru (U+0A32) contains a short segment L<<415.0,73.0>--<426.0,73.0>>

	* laguru (U+0A32) contains a short segment L<<254.0,0.0>--<248.0,0.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<415.0,73.0>--<426.0,73.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<254.0,0.0>--<248.0,0.0>>

	* haguru (U+0A39) contains a short segment B<<251.0,407.5>-<263.0,407.0>-<270.0,405.0>> 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[21] NotoSansGurmukhi-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi SemiBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nyanuktaprehalfguru
	* lanuktaprehalfguru
	* thaguru
	* auguru
	* banuktaguru
	* bhaguru
	* khanuktaprehalfguru
	* nnaprehalfguru
	* ddanuktaprehalfguru
	* vasubscriptuuguru and 70 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 587 but it should be 602 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.guru (U+002C): X=179.0,Y=-1.0 (should be at baseline 0?)

	* zero.guru (U+0030): X=275.0,Y=620.0 (should be at cap-height 622?)

	* three.guru (U+0033): X=125.0,Y=-0.5 (should be at baseline 0?)

	* three.guru (U+0033): X=249.0,Y=620.0 (should be at cap-height 622?)

	* five.guru (U+0035): X=132.5,Y=-0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=86.0,Y=-2.0 (should be at baseline 0?)

	* semicolon.guru (U+003B): X=188.0,Y=-1.0 (should be at baseline 0?)

	* question.guru (U+003F): X=259.0,Y=620.0 (should be at cap-height 622?)

	* eeguru (U+0A0F): X=175.0,Y=894.0 (should be at ascender 896?)

	* eematraguru (U+0A47): X=-415.0,Y=894.0 (should be at ascender 896?) 

	* And 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<201.0,116.0>--<201.0,110.0>>

	* aiguru (U+0A10) contains a short segment B<<385.5,760.0>-<391.0,760.0>-<395.0,760.0>>

	* jaguru (U+0A1C) contains a short segment L<<105.0,271.0>--<89.0,271.0>>

	* jhaguru (U+0A1D) contains a short segment B<<250.0,69.0>-<241.0,69.0>-<232.0,69.0>>

	* jhaguru (U+0A1D) contains a short segment B<<305.0,416.0>-<306.0,416.0>-<306.0,416.0>>

	* ddaguru (U+0A21) contains a short segment B<<444.0,505.0>-<444.0,516.0>-<442.0,527.0>>

	* ddhaguru (U+0A22) contains a short segment L<<101.0,308.0>--<85.0,308.0>>

	* daguru (U+0A26) contains a short segment L<<101.0,277.0>--<85.0,277.0>>

	* bhaguru (U+0A2D) contains a short segment B<<426.0,407.0>-<429.0,418.0>-<430.0,428.5>>

	* bhaguru (U+0A2D) contains a short segment B<<430.0,428.5>-<431.0,439.0>-<431.0,448.0>> 

	* And 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nyaguru (U+0A1E): L<<244.0,453.0>--<250.0,453.0>> -> L<<250.0,453.0>--<391.0,453.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhi-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- umatralow1guru
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 527 but it should be 538 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.guru (U+0021): X=199.5,Y=1.0 (should be at baseline 0?)

	* exclam.guru (U+0021): X=157.0,Y=1.0 (should be at baseline 0?)

	* comma.guru (U+002C): X=82.0,Y=1.5 (should be at baseline 0?)

	* period.guru (U+002E): X=125.5,Y=1.0 (should be at baseline 0?)

	* period.guru (U+002E): X=83.0,Y=1.0 (should be at baseline 0?)

	* three.guru (U+0033): X=129.5,Y=-1.0 (should be at baseline 0?)

	* five.guru (U+0035): X=155.5,Y=2.0 (should be at baseline 0?)

	* nine.guru (U+0039): X=107.0,Y=-2.0 (should be at baseline 0?)

	* colon.guru (U+003A): X=96.0,Y=1.0 (should be at baseline 0?)

	* colon.guru (U+003A): X=138.5,Y=1.0 (should be at baseline 0?) 

	* And 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uguru (U+0A09): L<<548.0,578.0>--<548.0,592.0>> -> L<<548.0,592.0>--<548.0,596.0>>

	* uraguru (U+0A73): L<<548.0,578.0>--<548.0,592.0>> -> L<<548.0,592.0>--<548.0,596.0>> 

	* And uuguru (U+0A0A): L<<548.0,578.0>--<548.0,592.0>> -> L<<548.0,592.0>--<548.0,596.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.guru (U+0021): L<<167.0,174.0>--<165.0,714.0>> 

	* And exclam.guru (U+0021): L<<193.0,714.0>--<191.0,174.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 623 but it should be 644 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* braceleft.guru (U+007B): X=159.0,Y=2.0 (should be at baseline 0?)

	* oneguru (U+0A67): X=440.5,Y=2.0 (should be at baseline 0?)

	* threeguru (U+0A69): X=153.0,Y=621.0 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=454.0,Y=-0.5 (should be at baseline 0?)

	* sixguru (U+0A6C): X=466.0,Y=623.0 (should be at cap-height 622?)

	* nineguru (U+0A6F): X=513.0,Y=623.0 (should be at cap-height 622?)

	* ekonkarguru (U+0A74): X=448.5,Y=2.0 (should be at baseline 0?)

	* uni262C (U+262C): X=343.0,Y=1.0 (should be at baseline 0?)

	* uni262C (U+262C): X=258.0,Y=620.5 (should be at cap-height 622?)

	* uni262C (U+262C): X=692.0,Y=620.5 (should be at cap-height 622?)

	* uni262C (U+262C): X=607.0,Y=1.0 (should be at baseline 0?) 

	* And uniA837 (U+A837): X=447.0,Y=623.0 (should be at cap-height 622?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<274.0,163.0>--<274.0,158.0>>

	* iiguru (U+0A08) contains a short segment L<<706.0,622.0>--<706.0,635.0>>

	* chaguru (U+0A1B) contains a short segment B<<258.0,327.0>-<242.0,327.0>-<235.5,325.5>>

	* chaguru (U+0A1B) contains a short segment B<<235.5,325.5>-<229.0,324.0>-<226.0,322.0>>

	* chaguru (U+0A1B) contains a short segment B<<226.0,322.0>-<219.0,318.0>-<219.0,308.0>>

	* jaguru (U+0A1C) contains a short segment L<<88.0,221.0>--<84.0,221.0>>

	* nyaguru (U+0A1E) contains a short segment B<<125.0,189.0>-<117.0,192.0>-<109.0,195.0>>

	* nyaguru (U+0A1E) contains a short segment B<<221.5,325.5>-<215.0,324.0>-<212.0,322.0>>

	* nyaguru (U+0A1E) contains a short segment B<<212.0,322.0>-<205.0,318.0>-<205.0,308.0>>

	* nyaguru (U+0A1E) contains a short segment B<<205.0,308.0>-<205.0,298.0>-<214.0,293.0>> 

	* And 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 601 but it should be 619 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five.guru (U+0035): X=127.0,Y=-0.5 (should be at baseline 0?)

	* twoguru (U+0A68): X=136.5,Y=621.0 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=442.5,Y=1.0 (should be at baseline 0?)

	* eightguru (U+0A6E): X=497.0,Y=1.0 (should be at baseline 0?)

	* nineguru (U+0A6F): X=497.0,Y=1.0 (should be at baseline 0?)

	* uni262C (U+262C): X=343.0,Y=1.0 (should be at baseline 0?)

	* uni262C (U+262C): X=258.0,Y=620.5 (should be at cap-height 622?)

	* uni262C (U+262C): X=692.0,Y=620.5 (should be at cap-height 622?)

	* uni262C (U+262C): X=607.0,Y=1.0 (should be at baseline 0?)

	* uniA835 (U+A835): X=67.0,Y=-1.0 (should be at baseline 0?) 

	* And uniA837 (U+A837): X=450.0,Y=623.0 (should be at cap-height 622?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<228.0,134.0>--<228.0,127.0>>

	* aaguru (U+0A06) contains a short segment B<<355.5,395.5>-<350.0,415.0>-<345.0,424.0>>

	* aiguru (U+0A10) contains a short segment B<<403.5,760.0>-<409.0,760.0>-<413.0,760.0>>

	* auguru (U+0A14) contains a short segment L<<578.0,867.0>--<578.0,867.0>>

	* ghaguru (U+0A18) contains a short segment B<<580.0,249.0>-<592.0,253.0>-<601.0,260.0>>

	* chaguru (U+0A1B) contains a short segment B<<221.5,349.5>-<210.0,348.0>-<202.0,343.0>>

	* jaguru (U+0A1C) contains a short segment L<<104.0,259.0>--<89.0,259.0>>

	* nyaguru (U+0A1E) contains a short segment B<<201.0,349.0>-<189.0,347.0>-<183.0,342.0>>

	* nyaguru (U+0A1E) contains a short segment B<<276.0,176.0>-<267.0,173.0>-<262.0,169.0>>

	* nyaguru (U+0A1E) contains a short segment B<<262.0,169.0>-<253.0,162.0>-<253.0,150.0>> 

	* And 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nyaguru (U+0A1E): L<<257.0,451.0>--<257.0,451.0>> -> L<<257.0,451.0>--<388.0,451.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI ExtraBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 611 but it should be 631 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five.guru (U+0035): X=131.0,Y=-0.5 (should be at baseline 0?)

	* oneguru (U+0A67): X=443.0,Y=2.0 (should be at baseline 0?)

	* twoguru (U+0A68): X=138.0,Y=621.5 (should be at cap-height 622?)

	* threeguru (U+0A69): X=149.0,Y=620.5 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=447.5,Y=0.5 (should be at baseline 0?)

	* eightguru (U+0A6E): X=504.0,Y=1.5 (should be at baseline 0?)

	* nineguru (U+0A6F): X=504.0,Y=1.5 (should be at baseline 0?)

	* ekonkarguru (U+0A74): X=440.0,Y=2.0 (should be at baseline 0?)

	* uni262C (U+262C): X=343.0,Y=1.0 (should be at baseline 0?)

	* uni262C (U+262C): X=258.0,Y=620.5 (should be at cap-height 622?) 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<249.0,147.0>--<249.0,141.0>>

	* iiguru (U+0A08) contains a short segment B<<538.0,680.0>-<539.0,670.0>-<540.0,662.0>>

	* chaguru (U+0A1B) contains a short segment B<<228.0,338.5>-<219.0,337.0>-<213.0,333.0>>

	* chaguru (U+0A1B) contains a short segment B<<213.0,333.0>-<202.0,327.0>-<202.0,313.0>>

	* jaguru (U+0A1C) contains a short segment L<<97.0,241.0>--<87.0,241.0>>

	* jhaguru (U+0A1D) contains a short segment B<<311.0,418.0>-<311.0,418.0>-<313.0,418.0>>

	* nyaguru (U+0A1E) contains a short segment B<<210.5,338.0>-<201.0,336.0>-<196.0,333.0>>

	* nyaguru (U+0A1E) contains a short segment B<<196.0,333.0>-<187.0,326.0>-<187.0,314.0>>

	* nyaguru (U+0A1E) contains a short segment B<<289.5,173.0>-<281.0,171.0>-<276.0,167.0>>

	* nyaguru (U+0A1E) contains a short segment B<<276.0,167.0>-<268.0,161.0>-<268.0,150.0>> 

	* And 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 535 but it should be 547 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.guru (U+0021): X=210.5,Y=1.5 (should be at baseline 0?)

	* exclam.guru (U+0021): X=158.5,Y=1.5 (should be at baseline 0?)

	* comma.guru (U+002C): X=80.0,Y=0.5 (should be at baseline 0?)

	* period.guru (U+002E): X=136.0,Y=1.5 (should be at baseline 0?)

	* period.guru (U+002E): X=84.5,Y=1.5 (should be at baseline 0?)

	* two.guru (U+0032): X=91.0,Y=623.0 (should be at cap-height 622?)

	* three.guru (U+0033): X=129.0,Y=-1.5 (should be at baseline 0?)

	* five.guru (U+0035): X=152.5,Y=1.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=105.0,Y=-2.0 (should be at baseline 0?)

	* colon.guru (U+003A): X=97.5,Y=1.5 (should be at baseline 0?) 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<102.0,39.0>--<102.0,37.0>>

	* uguru (U+0A09) contains a short segment L<<585.0,587.0>--<585.0,582.0>>

	* uuUIguru (U+0A0A) contains a short segment L<<585.0,587.0>--<585.0,582.0>>

	* aiguru (U+0A10) contains a short segment B<<350.0,855.0>-<345.0,855.0>-<341.0,855.0>>

	* aiguru (U+0A10) contains a short segment L<<595.0,613.0>--<597.0,611.0>>

	* ooguru (U+0A13) contains a short segment L<<585.0,587.0>--<585.0,584.0>>

	* jaguru (U+0A1C) contains a short segment L<<104.0,324.0>--<93.0,324.0>>

	* jaguru (U+0A1C) contains a short segment B<<120.0,424.0>-<134.0,424.0>-<138.5,412.5>>

	* ddhaguru (U+0A22) contains a short segment L<<93.0,352.0>--<81.0,352.0>>

	* ddhaguru (U+0A22) contains a short segment B<<49.5,357.5>-<38.0,363.0>-<38.0,376.0>> 

	* And 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 546 but it should be 559 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.guru (U+002C): X=78.0,Y=-0.5 (should be at baseline 0?)

	* three.guru (U+0033): X=129.0,Y=-1.5 (should be at baseline 0?)

	* five.guru (U+0035): X=148.5,Y=0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=103.0,Y=-1.0 (should be at baseline 0?)

	* semicolon.guru (U+003B): X=75.5,Y=-0.5 (should be at baseline 0?)

	* oneguru (U+0A67): X=317.0,Y=620.0 (should be at cap-height 622?)

	* eightguru (U+0A6E): X=460.5,Y=1.5 (should be at baseline 0?)

	* nineguru (U+0A6F): X=460.0,Y=1.5 (should be at baseline 0?)

	* ekonkarguru (U+0A74): X=311.0,Y=620.0 (should be at cap-height 622?)

	* uni262C (U+262C): X=343.0,Y=1.0 (should be at baseline 0?) 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<122.0,56.0>--<122.0,54.0>>

	* aaguru (U+0A06) contains a short segment B<<331.0,123.0>-<317.0,123.0>-<308.0,132.5>>

	* aaguru (U+0A06) contains a short segment B<<92.0,225.0>-<78.0,225.0>-<69.0,234.5>>

	* aiguru (U+0A10) contains a short segment B<<359.5,843.0>-<355.0,843.0>-<351.0,843.0>>

	* aiguru (U+0A10) contains a short segment B<<604.0,612.0>-<606.0,609.0>-<608.0,606.0>>

	* jaguru (U+0A1C) contains a short segment L<<105.0,312.0>--<91.0,312.0>>

	* ddhaguru (U+0A22) contains a short segment L<<96.0,340.0>--<82.0,340.0>>

	* daguru (U+0A26) contains a short segment L<<96.0,312.0>--<82.0,312.0>>

	* laguru (U+0A32) contains a short segment L<<408.0,50.0>--<419.0,50.0>>

	* laguru (U+0A32) contains a short segment L<<245.0,0.0>--<238.0,0.0>> 

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 576 but it should be 590 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.guru (U+0033): X=127.0,Y=-1.0 (should be at baseline 0?)

	* five.guru (U+0035): X=138.0,Y=-0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=92.0,Y=-2.0 (should be at baseline 0?)

	* question.guru (U+003F): X=178.5,Y=620.5 (should be at cap-height 622?)

	* khanuktaguru (U+0A59): X=125.5,Y=0.5 (should be at baseline 0?)

	* khanuktaguru (U+0A59): X=215.0,Y=0.5 (should be at baseline 0?)

	* oneguru (U+0A67): X=333.5,Y=621.0 (should be at cap-height 622?)

	* twoguru (U+0A68): X=133.0,Y=621.0 (should be at cap-height 622?)

	* threeguru (U+0A69): X=140.0,Y=620.0 (should be at cap-height 622?)

	* sixguru (U+0A6C): X=425.0,Y=2.0 (should be at baseline 0?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<177.0,99.0>--<177.0,95.0>>

	* auguru (U+0A14) contains a short segment B<<482.0,755.0>-<482.0,759.0>-<482.0,761.0>>

	* jaguru (U+0A1C) contains a short segment L<<105.0,282.0>--<88.0,282.0>>

	* jhaguru (U+0A1D) contains a short segment B<<298.0,413.0>-<300.0,413.0>-<301.0,413.0>>

	* ddhaguru (U+0A22) contains a short segment L<<101.0,314.0>--<84.0,314.0>>

	* daguru (U+0A26) contains a short segment L<<101.0,285.0>--<84.0,285.0>>

	* laguru (U+0A32) contains a short segment L<<421.0,85.0>--<432.0,85.0>>

	* laguru (U+0A32) contains a short segment L<<260.0,0.0>--<254.0,0.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<421.0,85.0>--<432.0,85.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<260.0,0.0>--<254.0,0.0>> 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansGurmukhiUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 565 but it should be 578 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.guru (U+0021): X=252.5,Y=2.0 (should be at baseline 0?)

	* exclam.guru (U+0021): X=165.0,Y=2.0 (should be at baseline 0?)

	* period.guru (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period.guru (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three.guru (U+0033): X=128.5,Y=-1.5 (should be at baseline 0?)

	* three.guru (U+0033): X=344.5,Y=620.5 (should be at cap-height 622?)

	* five.guru (U+0035): X=142.0,Y=-0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=98.0,Y=-1.0 (should be at baseline 0?)

	* nine.guru (U+0039): X=341.5,Y=621.5 (should be at cap-height 622?)

	* colon.guru (U+003A): X=103.0,Y=2.0 (should be at baseline 0?) 

	* And 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<156.0,85.0>--<156.0,81.0>>

	* khaguru (U+0A16) contains a short segment B<<188.0,460.0>-<188.0,456.0>-<188.0,454.0>>

	* jaguru (U+0A1C) contains a short segment L<<106.0,291.0>--<88.0,291.0>>

	* ddhaguru (U+0A22) contains a short segment L<<101.0,320.0>--<83.0,320.0>>

	* daguru (U+0A26) contains a short segment L<<101.0,291.0>--<83.0,291.0>>

	* laguru (U+0A32) contains a short segment L<<415.0,73.0>--<426.0,73.0>>

	* laguru (U+0A32) contains a short segment L<<254.0,0.0>--<248.0,0.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<415.0,73.0>--<426.0,73.0>>

	* lanuktaguru (U+0A33) contains a short segment L<<254.0,0.0>--<248.0,0.0>>

	* haguru (U+0A39) contains a short segment B<<251.0,407.5>-<263.0,407.0>-<270.0,405.0>> 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhiUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI SemiBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 587 but it should be 604 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.guru (U+002C): X=179.0,Y=-1.0 (should be at baseline 0?)

	* zero.guru (U+0030): X=275.0,Y=620.0 (should be at cap-height 622?)

	* three.guru (U+0033): X=125.0,Y=-0.5 (should be at baseline 0?)

	* three.guru (U+0033): X=249.0,Y=620.0 (should be at cap-height 622?)

	* five.guru (U+0035): X=132.5,Y=-0.5 (should be at baseline 0?)

	* nine.guru (U+0039): X=86.0,Y=-2.0 (should be at baseline 0?)

	* semicolon.guru (U+003B): X=188.0,Y=-1.0 (should be at baseline 0?)

	* question.guru (U+003F): X=259.0,Y=620.0 (should be at cap-height 622?)

	* oneguru (U+0A67): X=345.5,Y=620.0 (should be at cap-height 622?)

	* twoguru (U+0A68): X=134.5,Y=621.0 (should be at cap-height 622?) 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.guru (U+0032) contains a short segment L<<201.0,116.0>--<201.0,110.0>>

	* aiguru (U+0A10) contains a short segment B<<385.5,760.0>-<391.0,760.0>-<395.0,760.0>>

	* jaguru (U+0A1C) contains a short segment L<<105.0,271.0>--<89.0,271.0>>

	* jhaguru (U+0A1D) contains a short segment B<<250.0,69.0>-<241.0,69.0>-<232.0,69.0>>

	* jhaguru (U+0A1D) contains a short segment B<<305.0,416.0>-<306.0,416.0>-<306.0,416.0>>

	* ddaguru (U+0A21) contains a short segment B<<444.0,505.0>-<444.0,516.0>-<442.0,527.0>>

	* ddhaguru (U+0A22) contains a short segment L<<101.0,308.0>--<85.0,308.0>>

	* daguru (U+0A26) contains a short segment L<<101.0,277.0>--<85.0,277.0>>

	* bhaguru (U+0A2D) contains a short segment B<<426.0,407.0>-<429.0,418.0>-<430.0,428.5>>

	* bhaguru (U+0A2D) contains a short segment B<<430.0,428.5>-<431.0,439.0>-<431.0,448.0>> 

	* And 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nyaguru (U+0A1E): L<<244.0,453.0>--<250.0,453.0>> -> L<<250.0,453.0>--<391.0,453.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[20] NotoSansGurmukhiUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Gurmukhi UI Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 407, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gurmukhi UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- raUIguru

	- hasubscript1UIguru

	- vasubscripthalantUIguru

	- uuUIaddakguru

	- baUIguru

	- phuunuktaUIguru

	- umatralowUIguru

	- uunuktaUIaddakguru

	- sanuktaUIguru

	- uubindiUIguru 

	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.guru	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 527 but it should be 539 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 udaatUIguru (U+0A51), uumatraUIguru (U+0A42) and yakashUIguru (U+0A75) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.guru (U+0021): X=199.5,Y=1.0 (should be at baseline 0?)

	* exclam.guru (U+0021): X=157.0,Y=1.0 (should be at baseline 0?)

	* comma.guru (U+002C): X=82.0,Y=1.5 (should be at baseline 0?)

	* period.guru (U+002E): X=125.5,Y=1.0 (should be at baseline 0?)

	* period.guru (U+002E): X=83.0,Y=1.0 (should be at baseline 0?)

	* three.guru (U+0033): X=129.5,Y=-1.0 (should be at baseline 0?)

	* five.guru (U+0035): X=155.5,Y=2.0 (should be at baseline 0?)

	* nine.guru (U+0039): X=107.0,Y=-2.0 (should be at baseline 0?)

	* colon.guru (U+003A): X=96.0,Y=1.0 (should be at baseline 0?)

	* colon.guru (U+003A): X=138.5,Y=1.0 (should be at baseline 0?) 

	* And 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uguru (U+0A09): L<<548.0,578.0>--<548.0,592.0>> -> L<<548.0,592.0>--<548.0,596.0>>

	* uraguru (U+0A73): L<<548.0,578.0>--<548.0,592.0>> -> L<<548.0,592.0>--<548.0,596.0>> 

	* And uuUIguru (U+0A0A): L<<548.0,578.0>--<548.0,592.0>> -> L<<548.0,592.0>--<548.0,596.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.guru (U+0021): L<<167.0,174.0>--<165.0,714.0>> 

	* And exclam.guru (U+0021): L<<193.0,714.0>--<191.0,174.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansGurmukhi[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2019-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurmukhi/googlefonts/slim-variable-ttf/NotoSansGurmukhi[wght].ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhi-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Black.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Bold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-ExtraLight.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Light.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Medium.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Regular.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-SemiBold.ttf', 'fonts/NotoSansGurmukhi/googlefonts/ttf/NotoSansGurmukhiUI-Thin.ttf', 'fonts/NotoSansGurmukhi/googlefonts/variable-ttf/NotoSansGurmukhi[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 896 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.guru": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- udaatguru 

	- And yakashguru [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 292. [code: invalid-default-instance-subfamily-nameid:292]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- udaatuuUIguru

	- numbersign

	- semicolon

	- vasubscript1UIguru

	- parenleft

	- raUIguru

	- hasubscripthalantUIguru

	- quotedbl

	- four

	- greater 

	- And 68 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 visargaguru (U+0A03) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0A03 [code: non-mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 159 | 230 | 2265 | 141 | 1620 | 0 |
| 0% | 4% | 5% | 51% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
