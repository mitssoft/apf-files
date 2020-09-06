# apf-files
List files for use with apf-utility

Apf files are text files intended to be readable by apf-utility in order to import the file as an array available to a program. The lines not to be included in the array contain the prefix #\*@! and are considered comments unless they have a symbol at the end, like [#\*@!=] which means alias, [#\*@!SOF Title] which means start of file with a title, [#\*@!EOF] which means End Of File and [#\*@!Name] which means name of the returned array.
