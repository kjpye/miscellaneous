# miscellaneous
Miscellaneous short programs and scripts
## mkpass
Make random passwords where you can specify the length (default 15) and which ASCII characters can be used (defaults to all printable ASCII)
Options:
* <number> -- the number of characters inthe generated password
* ±punc -- odd or delete all punctuation from the allowed characters
* ±<alpha> -- add or delete all alphabetic characters
* ±<digit> -- add or delete all digits
* ±<punc> -- add or delete the specific character

When the first non-numeric option starts with a '+' the allowed characters are cleared first. Otherwise all characters are allowed, subject to the options.
