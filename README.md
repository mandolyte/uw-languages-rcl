# [uw-languages-rcl](https://unfoldingWord.github.io/uw-languages-rcl/)

A React Component Library for Languages

The source information will be from a JSON file `langnames.json` [here](https://td2.unfoldingword.org/exports/langnames.json). 
This is an array of objects, one per language. 

Here is an example:

```json
{
"pk": 7501,
"ang": "Zhuang, Zuojiang",
"lr": "Asia",
"gw": false,
"hc": "CN",
"ln": "\u5de6\u6c5f",
"lc": "zzj",
"ld": "ltr",
"alt": [
    "Ken Tho",
    "Longyin",
    "Longzhou",
    "Pho Thai",
    "Pu Tho",
    "Southern Zhuang",
    "Zhuangyu nanbu fangyan Zuojiang tuyu",
    "Nung Chao"
],
"cc": ["CN"]
}
```

The package essentially provide a custom React Hook which returns
state and actions (a small set of functions to use for language data).

The code in the `demos` folder are examples of using the custom hook.

## General Language Information

The Library of Congress has a list of language names with both 
two and three character codes (ISO 639-1 and 639-2, respectively).
Link: https://www.loc.gov/standards/iso639-2/php/English_list.php

The site https://iso639-3.sil.org/ has a link to download a number of 
language tables in TSV format (easy to import into a spreadsheet).

Direct link to download the tables:
https://iso639-3.sil.org/code_tables/download_tables

Of the ones available, this one combines common useful info:
https://iso639-3.sil.org/sites/iso639-3/files/downloads/iso-639-3.tab
