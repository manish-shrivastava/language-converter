Language-converter
===================

A Perfect Free language converter gem.

    gem install language-converter
    

Description :
============
Free Language converter that convert word or text from one language to another.

Dependencies :
============

* ruby 1.8.7, 1.9.2, or 1.9.3

Installation :
=============

You can do language conversion of word or text from one language to another language very easily.

    gem install language-converter

Example :
==========

Suppose, If you want to convert from `english` to `spanish`:

    require 'language_converter'
    lc 'welcome', 'es','en'

This will convert text "Welcome" (english word) to "Bienvenida" (spanish).

How to Use:
============

    lc( '<WORD/TEXT NEED TO BE TRANSLATED>', '<CONVERT_TO>','<CONVERT_FROM>')


---------------------------------------------------------------------------------------------------

* <tt>WORD/TEXT NEED TO BE TRANSLATED </tt>: Text word which you want to translate.

* <tt>CONVERT_TO</tt> : Language Code to which you want to convert.

* <tt>CONVERT_FROM</tt> : Language Code of text/word passed in first parameter (if not english).If you will not set `CONVERT_FROM` It will suppose you are converting from english to `CONVERT_TO` Language Code.

---------------------------------------------------------------------------------------------------


Put Language Code `af-ZA` for Afrikaans

Put Language Code `sq-AL` for Albanian

Put Language Code `am-AM` for Amharic

Put Language Code `ar-SA` for Arabic

Put Language Code `hy-AM` for Armenian

Put Language Code `az-AZ` for Azerbaijani

Put Language Code `bjs-BJS` for Bajan

Put Language Code `rm-RO` for Balkan Gipsy

Put Language Code `eu-ES` for Basque

Put Language Code `bem-BEM` for Bemba

Put Language Code `bn-IN` for Bengali

Put Language Code `be-BY` for Bielarus

Put Language Code `bi-BI` for Bislama

Put Language Code `bs-BA` for Bosnian

Put Language Code `br-FR` for Breton

Put Language Code `bg-BG` for Bulgarian

Put Language Code `my-MM` for Burmese

Put Language Code `ca-ES` for Catalan

Put Language Code `cb-PH` for Cebuano

Put Language Code `ch-CH` for Chamorro

Put Language Code `zh-CN` for Chinese (Simplified)

Put Language Code `zh-TW` for Chinese Traditional

Put Language Code `zdj-ZDJ` for Comorian (Ngazidja)

Put Language Code `cop-XNA` for Coptic

Put Language Code `aig-AIG` for Creole English (Antigua and Barbuda)

Put Language Code `bah-BAH` for Creole English (Bahamas)

Put Language Code `gcl-GCL` for Creole English (Grenadian)

Put Language Code `gyn-GYN` for Creole English (Guyanese)

Put Language Code `xx-JM` for Creole English (Jamaican)

Put Language Code `svc-SVC` for Creole English (Vincentian)

Put Language Code `vic-VIC` for Creole English (Virgin Islands)

Put Language Code `ht-HT` for Creole French (Haitian)

Put Language Code `acf-ACF` for Creole French (Saint Lucian)

Put Language Code `crs-CRS` for Creole French (Seselwa)

Put Language Code `pov-POV` for Creole Portuguese (Upper Guinea)

Put Language Code `hr-HR` for Croatian

Put Language Code `cs-CZ` for Czech

Put Language Code `da-DK` for Danish

Put Language Code `nl-NL` for Dutch

Put Language Code `dz-DZ` for Dzongkha

Put Language Code `en-GB` for English

Put Language Code `eo-XN` for Esperanto

Put Language Code `et-EE` for Estonian

Put Language Code `fn-FNG` for Fanagalo

Put Language Code `fo-FO` for Faroese

Put Language Code `fi-FI` for Finnish

Put Language Code `fr-FR` for French

Put Language Code `gl-ES` for Galician

Put Language Code `ka-GE` for Georgian

Put Language Code `de-DE` for German

Put Language Code `el-GR` for Greek

Put Language Code `XN-GR` for Greek (Classical)

Put Language Code `gu-IN` for Gujarati

Put Language Code `ha-HA` for Hausa

Put Language Code `XN-US` for Hawaiian

Put Language Code `he-IL` for Hebrew

Put Language Code `hi-IN` for Hindi

Put Language Code `hu-HU` for Hungarian

Put Language Code `is-IS` for Icelandic

Put Language Code `id-ID` for Indonesian

Put Language Code `kl-KL` for Inuktitut (Greenlandic)

Put Language Code `ga-IE` for Irish Gaelic

Put Language Code `it-IT` for Italian

Put Language Code `ja-JA` for Japanese

Put Language Code `jw-ID` for Javanese

Put Language Code `kea-KEA` for Kabuverdianu

Put Language Code `kab-DZ` for Kabylian

Put Language Code `ka-IN` for Kannada

Put Language Code `kk-KZ` for Kazakh

Put Language Code `km-KM` for Khmer

Put Language Code `rw-RW` for Kinyarwanda

Put Language Code `rn-RN` for Kirundi

Put Language Code `ko-KR` for Korean

Put Language Code `ku-TR` for Kurdish

Put Language Code `ku-TR` for Kurdish Sorani

Put Language Code `ky-KY` for Kyrgyz

Put Language Code `lo-LO` for Lao

Put Language Code `la-XN` for Latin

Put Language Code `lv-LV` for Latvian

Put Language Code `lt-LT` for Lithuanian

Put Language Code `lb-LB` for Luxembourgish

Put Language Code `mk-MK` for Macedonian

Put Language Code `mg-MG` for Malagasy

Put Language Code `ms-MY` for Malay

Put Language Code `dv-DV` for Maldivian

Put Language Code `mt-MT` for Maltese

Put Language Code `gv-IM` for Manx Gaelic

Put Language Code `mi-NZ` for Maori

Put Language Code `mh-MH` for Marshallese

Put Language Code `men-MEN` for Mende

Put Language Code `mn-MN` for Mongolian

Put Language Code `mfe-MFE` for Morisyen

Put Language Code `ne-NP` for Nepali

Put Language Code `niu-NIU` for Niuean

Put Language Code `no-NO` for Norwegian

Put Language Code `ny-NY` for Nyanja

Put Language Code `ur-PK` for Pakistani

Put Language Code `pau-PAU` for Palauan

Put Language Code `pa-IN` for Panjabi

Put Language Code `pap-PAP` for Papiamentu

Put Language Code `ps-PK` for Pashto

Put Language Code `fa-IR` for Persian

Put Language Code `pis-PIS` for Pijin

Put Language Code `pl-PL` for Polish

Put Language Code `pt-PT` for Portuguese

Put Language Code `pot-US` for Potawatomi

Put Language Code `qu-XN` for Quechua

Put Language Code `ro-RO` for Romanian

Put Language Code `ru-RU` for Russian

Put Language Code `sm-SM` for Samoan

Put Language Code `sg-SG` for Sango

Put Language Code `gd-GB` for Scots Gaelic

Put Language Code `sr-RS` for Serbian

Put Language Code `sn-SN` for Shona

Put Language Code `si-LK` for Sinhala

Put Language Code `sk-SK` for Slovak

Put Language Code `sl-SI` for Slovenian

Put Language Code `so-SO` for Somali

Put Language Code `st-ST` for Sotho, Southern

Put Language Code `es-ES` for Spanish

Put Language Code `srn-SRN` for Sranan Tongo

Put Language Code `sw-SZ` for Swahili

Put Language Code `sv-SE` for Swedish

Put Language Code `de-CH` for Swiss German

Put Language Code `syc-TR` for Syriac (Aramaic)

Put Language Code `tl-PH` for Tagalog

Put Language Code `tg-TJ` for Tajik

Put Language Code `tmh-DZ` for Tamashek (Tuareg)

Put Language Code `ta-LK` for Tamil

Put Language Code `te-IN` for Telugu

Put Language Code `tet-TET` for Tetum

Put Language Code `th-TH` for Thai

Put Language Code `bo-CN` for Tibetan

Put Language Code `ti-TI` for Tigrinya

Put Language Code `tpi-TPI` for Tok Pisin

Put Language Code `tkl-TKL` for Tokelauan

Put Language Code `to-TO` for Tongan

Put Language Code `tn-TN` for Tswana

Put Language Code `tr-TR` for Turkish

Put Language Code `tk-TK` for Turkmen

Put Language Code `tvl-TVL` for Tuvaluan

Put Language Code `uk-UA` for Ukrainian

Put Language Code `ppk-ID` for Uma

Put Language Code `uz-UZ` for Uzbek

Put Language Code `vi-VN` for Vietnamese

Put Language Code `wls-WLS` for Wallisian

Put Language Code `cy-GB` for Welsh

Put Language Code `wo-SN` for Wolof

Put Language Code `xh-ZA` for Xhosa

Put Language Code `yi-YD` for Yiddish

Put Language Code `zu-ZU` for Zulu







== Authors

Copyright (c) 20012 by Manish Shrivastava (er.manishshrivastava@gmail.com)

Copyright (c) 2011-2012:

* {Manish Shrivastava}[http://www.facebook.com/Querybarry] (er.manishshrivastava@gmail.com)

Copyright (c) 2011-2012:

* {Manish Shrivastava}[http://www.facebook.com/Querybarry] (er.manishshrivastava@gmail.com)
Ruby, my favorite language!

== Acknowledgments

Thank you to CIS for starting the Ruby version.  Thanks to everyone
who's helped out in various ways.  Finally, thank you to the people using this
library!

== License

This library is distributed under the MIT license.  Please see the LICENSE file.
