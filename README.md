# keyboards
These are custom keyboard layouts that I use in the Microsoft KLC and the [XKB formats](https://en.wikipedia.org/wiki/X_keyboard_extension).

## Layouts

### fr_de_US
This is a regular US keyboards with extra characters accessible using the `AltGr` key.

Although the keyboard is designed mainly for easy access to French and German characters&mdash;including the often missing œ/Œ, æ/Æ and capital ẞ&mdash;more diacritics and characters are available, including those needed for Spanish, Portuguese, Romanian, and [ALA-LC romanization of Arabic](https://en.wikipedia.org/wiki/Romanization_of_Arabic#Comparison_table) among others.

Five sets of quotation marks are available: «…» “…” ‘…’ „…“ and ‚…‘.

As long as `AltGr` is not used, this keyboard is identical to the [US layout](https://en.wikipedia.org/wiki/QWERTY#United_States).

#### French diacritics and characters

* Acute accent (_accent aigu_): `AltGr`+`'`
* Grave accent (_accent grave_): `AltGr`+`` ` ``
* Circumflex (_accent circonflexe_): `AltGr`+`6`
* Diaeresis (_tréma_): `AltGr`+`;`
* Cedilla (_cédille_): `AltGr`+`\`
* Æ/æ ligature: `AltGt`+`A/a`
* Œ/œ ligature: `AltGt`+`O/o`
* «Guillemets»: `AltGr`+`,` and `AltGr`+`.`

#### German diacritics and characters

* Umlaut: `AltGr`+`;`
* ẞ/ß: `AltGr`+`S/s`
* „German double quotes“: `AltGr`+`9` and `AltGr`+`0`
* ‚German single quotes‘: `AltGr`+`(` and `AltGr`+`)`

#### Other diacritics

* Tilde: `AltGr`+`~`
* Comma below: `AltGr`+`<`
* Dot below: `AltGr`+`>`
* Macron: `AltGr`+`-`
* Breve: `AltGr`+`_`

#### Other punctuation

* “Double quotes”: `AltGr`+`[` and `AltGr`+`]`
* ‘Single quotes’: `AltGr`+`{` and `AltGr`+`}`
* Inverted exclamation mark ¡: `AltGr`+`1`
* Inverted question mark ¿: `AltGr`+`/`

#### Other characters

* Thorn Þ/þ: `AltGr`+`T/t`
* Eth Ð/ð: `AltGr`+`D/d`
* Mu µ: `AltGr`+`m`
* Cent sign ¢: `AltGr`+`4`
* Euro sign €: `AltGr`+`5`
* Pound sign £: `AltGr`+`%`
* Degree sign °: `AltGr`+`8`
* Multiplication ×: `AltGr`+`=`
* Division ÷: `AltGr`+`+`

### ar_US
This is an Arabic keyboard loosely based on the US layout.

Where feasible, Arabic letters are found on their most phonetically close Latin equivalent. Plain/[emphatic](https://en.wikipedia.org/wiki/Emphatic_consonant) pairs (e.g. س/ص) are on the same key (e.g. `s`), the emphatic letter being accessed with `Shift`.

Besides Arabic characters, this keyboard includes Persian letters as well as extra letters used in [Tunisian Arabic](https://en.wikipedia.org/wiki/Tunisian_Arabic#Arabic_script) for non-native sounds (پ=`/p/`, ڨ=`/ɡ/`, ڥ=`/v/`).

This keyboard also includes both [Eastern Arabic and Persian numerals](https://en.wikipedia.org/wiki/Eastern_Arabic_numerals).

## Installation
On Ubuntu, follow the instructions [here](https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions).

On Windows, download [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339), open the `klc` files and generate an executable.
