# miscellaneous
Miscellaneous short programs and scripts
## mkpass
Make random passwords where you can specify the length (default 15) and which ASCII characters can be used (defaults to all printable ASCII)
Options:
* &lt;number&gt; -- the number of characters in the generated password
* ±punc -- odd or delete all punctuation from the allowed characters
* ±&lt;alpha&gt; -- add or delete all alphabetic characters
* ±&lt;digit&gt; -- add or delete all digits
* ±&lt;punc&gt; -- add or delete the specific character

When the first non-numeric option starts with a '+' the allowed characters are cleared first. Otherwise all characters are allowed, subject to the options.
