# wikidict-dsl-no - Wikidata Bilingual DSL Dictionaries (Norwegian)

This repository makes available a collection of bilingual Norwegian dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-no/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-no_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-no` | Afrikaans => Norwegian
`am-no` | Amharic => Norwegian
`ang-no` | Anglo-Saxon => Norwegian
`ar-no` | Arabic => Norwegian
`arc-no` | Aramaic => Norwegian
`bg-no` | Bulgarian => Norwegian
`bi-no` | Bislama => Norwegian
`bn-no` | Bengali => Norwegian
`bo-no` | Tibetan => Norwegian
`br-no` | Breton => Norwegian
`bs-no` | Bosnian => Norwegian
`ca-no` | Catalan => Norwegian
`cdo-no` | Min Dong => Norwegian
`chr-no` | Cherokee => Norwegian
`chy-no` | Cheyenne => Norwegian
`cr-no` | Cree => Norwegian
`cs-no` | Czech => Norwegian
`cy-no` | Welsh => Norwegian
`da-no` | Danish => Norwegian
`de-no` | German => Norwegian
`el-no` | Greek => Norwegian
`en-no` | English => Norwegian
`eo-no` | Esperanto => Norwegian
`es-no` | Spanish => Norwegian
`et-no` | Estonian => Norwegian
`eu-no` | Basque => Norwegian
`fa-no` | Persian => Norwegian
`ff-no` | Fula => Norwegian
`fi-no` | Finnish => Norwegian
`fr-no` | French => Norwegian
`ga-no` | Irish => Norwegian
`gan-no` | Gan => Norwegian
`gd-no` | Scottish Gaelic => Norwegian
`gu-no` | Gujarati => Norwegian
`gv-no` | Manx => Norwegian
`ha-no` | Hausa => Norwegian
`hak-no` | Hakka => Norwegian
`haw-no` | Hawaiian => Norwegian
`he-no` | Hebrew => Norwegian
`hi-no` | Hindi => Norwegian
`hr-no` | Croatian => Norwegian
`ht-no` | Haitian => Norwegian
`hu-no` | Hungarian => Norwegian
`hy-no` | Armenian => Norwegian
`id-no` | Indonesian => Norwegian
`ig-no` | Igbo => Norwegian
`is-no` | Icelandic => Norwegian
`it-no` | Italian => Norwegian
`iu-no` | Inuktitut => Norwegian
`ja-no` | Japanese => Norwegian
`jbo-no` | Lojban => Norwegian
`jv-no` | Javanese => Norwegian
`ka-no` | Georgian => Norwegian
`kg-no` | Kongo => Norwegian
`ki-no` | Kikuyu => Norwegian
`kl-no` | Greenlandic => Norwegian
`km-no` | Khmer => Norwegian
`ko-no` | Korean => Norwegian
`la-no` | Latin => Norwegian
`lg-no` | Luganda => Norwegian
`lo-no` | Lao => Norwegian
`lt-no` | Lithuanian => Norwegian
`lv-no` | Latvian => Norwegian
`mg-no` | Malagasy => Norwegian
`mi-no` | Maori => Norwegian
`mn-no` | Mongolian => Norwegian
`ms-no` | Malay => Norwegian
`mt-no` | Maltese => Norwegian
`nah-no` | Nahuatl => Norwegian
`ne-no` | Nepali => Norwegian
`nl-no` | Dutch => Norwegian
`nn-no` | Norwegian (Nynorsk) => Norwegian
`nv-no` | Navajo => Norwegian
`ny-no` | Chichewa => Norwegian
`oc-no` | Occitan => Norwegian
`pa-no` | Punjabi => Norwegian
`pi-no` | Pali => Norwegian
`pl-no` | Polish => Norwegian
`ps-no` | Pashto => Norwegian
`pt-no` | Portuguese => Norwegian
`qu-no` | Quechua => Norwegian
`ro-no` | Romanian => Norwegian
`ru-no` | Russian => Norwegian
`sa-no` | Sanskrit => Norwegian
`se-no` | Northern Sami => Norwegian
`sh-no` | Serbo-Croatian => Norwegian
`sk-no` | Slovak => Norwegian
`sl-no` | Slovenian => Norwegian
`sn-no` | Shona => Norwegian
`so-no` | Somali => Norwegian
`sq-no` | Albanian => Norwegian
`sr-no` | Serbian => Norwegian
`sv-no` | Swedish => Norwegian
`sw-no` | Kiswahili => Norwegian
`ta-no` | Tamil => Norwegian
`te-no` | Telugu => Norwegian
`th-no` | Thai => Norwegian
`tl-no` | Tagalog => Norwegian
`tpi-no` | Tok Pisin => Norwegian
`tr-no` | Turkish => Norwegian
`ug-no` | Uyghur => Norwegian
`uk-no` | Ukrainian => Norwegian
`ur-no` | Urdu => Norwegian
`vi-no` | Vietnamese => Norwegian
`wo-no` | Wolof => Norwegian
`wuu-no` | Wu => Norwegian
`xh-no` | Xhosa => Norwegian
`yi-no` | Yiddish => Norwegian
`yo-no` | Yoruba => Norwegian
`za-no` | Zhuang => Norwegian
`zh-no` | Chinese (Mandarin) => Norwegian
`zh_classical-no` | Classical Chinese => Norwegian
`zh_min_nan-no` | Min Nan => Norwegian
`zh_yue-no` | Cantonese => Norwegian
`zu-no` | Zulu => Norwegian

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-no` | 18319
`am-no` | 5131
`ang-no` | 1982
`ar-no` | 66329
`arc-no` | 1194
`bg-no` | 58976
`bi-no` | 393
`bn-no` | 14355
`bo-no` | 2326
`br-no` | 21344
`bs-no` | 19857
`ca-no` | 85377
`cdo-no` | 1871
`chr-no` | 415
`chy-no` | 457
`cr-no` | 80
`cs-no` | 83993
`cy-no` | 21714
`da-no` | 84988
`de-no` | 191533
`el-no` | 37914
`en-no` | 275467
`eo-no` | 58989
`es-no` | 150560
`et-no` | 45346
`eu-no` | 45838
`fa-no` | 82643
`ff-no` | 177
`fi-no` | 109913
`fr-no` | 193385
`ga-no` | 17116
`gan-no` | 4431
`gd-no` | 9785
`gu-no` | 3020
`gv-no` | 3444
`ha-no` | 330
`hak-no` | 2516
`haw-no` | 549
`he-no` | 59368
`hi-no` | 18038
`hr-no` | 43616
`ht-no` | 6568
`hu-no` | 72585
`hy-no` | 28306
`id-no` | 57135
`ig-no` | 648
`is-no` | 19822
`it-no` | 168314
`iu-no` | 329
`ja-no` | 117884
`jbo-no` | 1103
`jv-no` | 12855
`ka-no` | 33444
`kg-no` | 565
`ki-no` | 224
`kl-no` | 1507
`km-no` | 1237
`ko-no` | 77940
`la-no` | 35204
`lg-no` | 139
`lo-no` | 937
`lt-no` | 46289
`lv-no` | 28425
`mg-no` | 14334
`mi-no` | 1988
`mn-no` | 8578
`ms-no` | 32808
`mt-no` | 1616
`nah-no` | 6035
`ne-no` | 5387
`nl-no` | 157002
`nn-no` | 71567
`nv-no` | 1235
`ny-no` | 77
`oc-no` | 22411
`pa-no` | 6715
`pi-no` | 2164
`pl-no` | 161352
`ps-no` | 2054
`pt-no` | 137179
`qu-no` | 9803
`ro-no` | 66230
`ru-no` | 160452
`sa-no` | 4242
`se-no` | 5977
`sh-no` | 45962
`sk-no` | 45201
`sl-no` | 35622
`sn-no` | 1310
`so-no` | 2077
`sq-no` | 17933
`sr-no` | 57150
`sv-no` | 162466
`sw-no` | 13344
`ta-no` | 16028
`te-no` | 6194
`th-no` | 35263
`tl-no` | 19794
`tpi-no` | 764
`tr-no` | 62165
`ug-no` | 2014
`uk-no` | 92595
`ur-no` | 17619
`vi-no` | 70162
`wo-no` | 791
`wuu-no` | 1823
`xh-no` | 231
`yi-no` | 5997
`yo-no` | 12355
`za-no` | 622
`zh-no` | 112910
`zh_classical-no` | 2034
`zh_min_nan-no` | 8044
`zh_yue-no` | 14112
`zu-no` | 508

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`en-no` | 275467
`fr-no` | 193385
`de-no` | 191533
`it-no` | 168314
`sv-no` | 162466
`pl-no` | 161352
`ru-no` | 160452
`nl-no` | 157002
`es-no` | 150560
`pt-no` | 137179

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
