# ELAN-templates
Some pre-designed ELAN templates (.etf) that work for ELAN-FLEx-ELAN workflows. 

## How to use these templates
ELAN-FLEx exports use the suffixes at the end of the tier names to make sure the right data goes in the correct fields in the resulting FLEx text and that the data is appropriately coded by language. For example, the suffix "-txt" followed by "-yaa" indicates that the data corresponds to the "Baseline" in FLEx and is in the Yaminahua language; the suffix "-gls" followed by "-es" indicates that the data in that tier consists of free translations to Spanish. These parts of the template tier names should not be changed! The participant label prefixes ("A_") may be changed or deleted if desired. 

The templates provided here use placeholders (e.g., 'xxx', 'yy', 'zz') in tier name suffixes for the FLEx internal language codes. The user will need to change these to the codes used in their FLEx project. The suffix "xxx" corresponds to the the "vernacular" language (i.e., the language being documented), and the suffixes "yy" and "zz" correspond to "analysis" languages (i.e., the language(s) used for translations or other analyses). 

Most languages FLEx codes correspond to the ISO 639-3 code, but some widely used languages like English (en) and Spanish (es) have two-character codes. The FLEx internal code can be checked in FLEx by going to Tools > Configure > Set up Vernacular/Analysis Writing Systems. The internal code is displayed under the "General" tab. Note that the code labeled "Language Code" is the ISO code, NOT the internal code. 

## About these templates
This repository contains the following templates:

### Multilingual-translations.etf
This template supports multilingual translations into two analysis languages (placeholder suffixes "yy" and "zz"), as well as participant labels which appear in the Notes field in FLEx (can be specified as either of the analysis languages).

### Basic-en.etf
This template supports translation into a single analysis language and has a notes field that does **not** show up in FLEx. This version of the template has English tier names.

### Basic-es.etf
This template supports translation into a single analysis language and has a notes field that does **not** show up in FLEx. THis version of the template has Spanish tier names.
