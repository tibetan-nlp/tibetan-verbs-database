# Tibetan Verbs Database (TVD)

This repository aims at being a database of Tibetan verbs in their four forms (past, present, future, imperative).

## Sources

Its sources (tagged in each verb) are:

- TDCM: བོད་རྒྱ་ཚིག་མཛོད་ཆེན་མོ།, 1993 (available on the [TBRC](http://www.tbrc.org/#library_work_ViewInWIndow-W29329|I1KG15044|3|1|829|876))
- GT: དུས་གསུམ་རེའུ་མིག་ཐུ་མིའི་དགོངས་གཏེར། by རྩོམ་པ་པོ་མཁར་སྟོད་རྡོ་རྗེ་དབང་ཕྱུག།, 1964
- PH: *A Tibetan Verb Lexicon* by Paul G. Hackett
- KN: དུས་གསུམ་རྣམ་གཞག། by Khenpo Karma Namgyal, edited by Vajra Vidhya, available on [dharmadownload.net](http://www.dharmadownload.net/pages/english/Texts/texts_0038.htm)

Other sources would be welcome:

- དག་ཡིག་གསར་བསྒྲིགཀ།, unknown date (quite recent), apparently a reference in Tibet

## Exceptions

The auxiliary ཤོག་ present in PH has not been added in this database.

## Method

The initial idea was to make a list with the correct forms of as many verbs as possible, with the second suffix ད. This is impossible though, as each Tibetan grammarian can have a different point of view on verb forms (which is surprising for a Westerner). So this database contains the raw data from the different sources, untouched: no choice has been made about the correctness of the different forms.

## What can I do with it?

There are already many things possible with this database (available thought the [database.py](database.py) script:

- get all syllables that may contain a second suffix ད
- get all syllables that may be verbs
- research one syllable in the database

If you want to constitute a simple verb list with translation or so, you'll have to merge the lists by hand and choose between the different forms. The script may help you with that in the future.

## Format

The database is in [CSV](https://en.wikipedia.org/wiki/Comma-separated_values), easily readable by any text editor, [LibreOffice Calc](https://fr.libreoffice.org/download/libreoffice-fresh/) or Microsoft Excel (requiring [a few steps](https://www.itg.ias.edu/content/how-import-csv-file-uses-utf-8-character-encoding-0)).

Each source is indicated in the 5, 6 or 7th column, by *TDC*, *PH* or *GT*. 

The order is present, past, future, imperative.

The database is separated in multiple files, one by letter. They are in alphabetical order.

Second suffix ད is indicated between tibetan parenthesis: ༼ད༽. Alternate ortographies are also indicated between tibetan parenthesis.

## Contributing

There are dozens of Tibetan books and dictionaries about verbs, contributions are very welcome, especially on providing sources, scanned or in Unicode.

## What about copyright?

There is (to the extend of the author's knowledge) no copyright on languages, so no copyright on grammar. According to their authors, these lists are part of the Tibetan grammar (each grammarian thinks his verb list is the real Tibetan verb list), so there is no copyright on the verb list. 

There is a copyright on the source books edition and also on the definition of the verbs given in these sources, but these do no appear in this database.

So this database has no copyright and can be considered public domain. If you really need a copyright, you can consider it is under the [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed) license.
