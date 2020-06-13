# SwearingWords

This repository contains a word list and extended word list of bad words in different languages.

## File Naming
```
words_<Language>(-extended).txt
```

## Languages
- de -> German
- en -> English

## Format
Each line contains a word. With a wait between 0 and 5,000,000
```
<Word>-<Wheight>
```

## Ignored Chars
Ignored chars shouldn't be in the dataset and will be stripped out of the entered message.
```Regex
[ !\"§$%&/()=?+*#'\\-_.:,;<>|~{}\\[\\]0-9]
```
