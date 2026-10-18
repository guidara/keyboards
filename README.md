# keyboards

These are custom keyboard layouts that I use in the Microsoft KLC and the
[XKB formats](https://en.wikipedia.org/wiki/X_keyboard_extension).

## Layouts

### ar_US

This is an Arabic keyboard loosely based on the US layout.

Where feasible, Arabic letters are found on their most phonetically close Latin equivalent.
Plain/[emphatic](https://en.wikipedia.org/wiki/Emphatic_consonant) pairs are on the same keys, the emphatic letters
being accessed with <kbd>Shift</kbd>. For example: <kbd>s</kbd>→س, <kbd>S</kbd>→ص.

Besides Arabic characters, this keyboard includes:

- Persian and Urdu letters;
- [Tunisian Arabic](https://en.wikipedia.org/wiki/Tunisian_Arabic#Arabic_script) characters for non-native sounds
  (پ=`/p/`, ڨ=`/ɡ/`, ڥ=`/v/`);
- Other [additional Arabic letters](https://en.wikipedia.org/wiki/Arabic_alphabet#Additional_letters) for regional variations and non-native sounds.

This keyboard also includes both [Eastern Arabic and Persian numerals](https://en.wikipedia.org/wiki/Eastern_Arabic_numerals).

#### Table of characters

|      Key      |    Base     | <kbd>Shift</kbd> | <kbd>AltGr</kbd> | <kbd>AltGr</kbd> + <kbd>Shift</kbd> |
| :-----------: | :---------: | :--------------: | :--------------: | :---------------------------------: |
| <kbd>`</kbd>  |     ◌ّ      |        ◌ْ        |        `         |                  ~                  |
| <kbd>1</kbd>  |      1      |        !         |        ١         |                  ۱                  |
| <kbd>2</kbd>  |      2      |        @         |        ٢         |                  ۲                  |
| <kbd>3</kbd>  |      3      |        #         |        ٣         |                  ۳                  |
| <kbd>4</kbd>  |      4      |        $         |        ٤         |                  ۴                  |
| <kbd>5</kbd>  |      5      |        %         |        ٥         |                  ۵                  |
| <kbd>6</kbd>  |      6      |        ^         |        ٦         |                  ۶                  |
| <kbd>7</kbd>  |      7      |        &         |        ٧         |                  ۷                  |
| <kbd>8</kbd>  |      8      |        \*        |        ٨         |                  ۸                  |
| <kbd>9</kbd>  |      9      |        )         |        ٩         |                  ۹                  |
| <kbd>0</kbd>  |      0      |        (         |        ٠         |                  ۰                  |
| <kbd>-</kbd>  |      -      |       ◌ـ◌        |        \_        |                                     |
| <kbd>=</kbd>  |      =      |        +         |        ×         |                  ÷                  |
| <kbd>q</kbd>  |      ق      |        ڨ         |        ڧ         |                  ٯ                  |
| <kbd>w</kbd>  |      و      |                  |                  |                                     |
| <kbd>e</kbd>  |      ع      |                  |                  |                                     |
| <kbd>r</kbd>  |      ر      |        ژ         |        ڑ         |                                     |
| <kbd>t</kbd>  |      ت      |        ط         |        ٹ         |                                     |
| <kbd>y</kbd>  |    يـ ي     |       ىـ ى       |       یـ ی       |                  ے                  |
| <kbd>u</kbd>  |      ؤ      |        ؤ         |                  |                                     |
| <kbd>i</kbd>  |      ئ      |        إ         |        ۓ         |                                     |
| <kbd>o</kbd>  |      أ      |        آ         |        ۂ         |                                     |
| <kbd>p</kbd>  |      ء      |        ◌ٔ        |                  |                                     |
| <kbd>[</kbd>  |     ◌ُ      |        ◌ٌ        |        ]         |                  }                  |
| <kbd>]</kbd>  |     ◌ِ      |        ◌ٍ        |        [         |                  {                  |
| <kbd>\\</kbd> |     ◌َ      |        ◌ً        |        \         |                 \|                  |
| <kbd>a</kbd>  |      ا      |        ة         |        ۃ         |                                     |
| <kbd>s</kbd>  |      س      |        ص         |                  |                                     |
| <kbd>d</kbd>  |      د      |        ض         |        ڈ         |                                     |
| <kbd>f</kbd>  |      ف      |        ڥ         |        ڤ         |                  ڢ                  |
| <kbd>g</kbd>  |      غ      |        گ         |                  |                                     |
| <kbd>h</kbd>  | هـ ـهـ ـه ه |        ح         |   ہـ ـہـ ـہ ہ    |                  ھ                  |
| <kbd>j</kbd>  |      ج      |        چ         |                  |                                     |
| <kbd>k</kbd>  |      ك      |        ک         |        ڭ         |                  ݣ                  |
| <kbd>l</kbd>  |      ل      |                  |                  |                                     |
| <kbd>;</kbd>  |      ؛      |        :         |                  |                                     |
| <kbd>'</kbd>  |      '      |        "         |                  |                                     |
| <kbd>z</kbd>  |      ز      |        ظ         |                  |                                     |
| <kbd>x</kbd>  |      خ      |                  |                  |                                     |
| <kbd>c</kbd>  |      ش      |                  |                  |                                     |
| <kbd>v</kbd>  |      ذ      |        ث         |                  |                                     |
| <kbd>b</kbd>  |      ب      |        پ         |                  |                                     |
| <kbd>n</kbd>  |      ن      |        ں         |        ◌٘        |                                     |
| <kbd>m</kbd>  |      م      |                  |                  |                                     |
| <kbd>,</kbd>  |      ،      |        »         |        ”         |                  <                  |
| <kbd>.</kbd>  |      .      |        «         |        “         |                  >                  |
| <kbd>/</kbd>  |      /      |        ؟         |                  |                                     |

## Installation

On Ubuntu, follow the instructions [here](https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions) or
[here](https://dev.to/szabi/custom-keyboard-layout-in-gnu-linux-i5f).

On Windows, download [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339),
open the `klc` files and generate an executable. Alternatively, download and run the installers.
