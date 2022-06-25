# Remove extra space from text with regex - Python

[toc]

Easy way to remove extra spaces from text, paragraph with regex in python

- Import regular expression packages

```Python
import re
```
- Remove extra spaces from text.

```Python
text = "  Hi python   is a case   sensitive language.    "
text = re.sub(' +', ' ', text)
print("text : ", text)
```

Explanation for above piece of code :
1. re.sub() - is a function in used to replace sub-string with another sub-string.
2. first argument in sub function is regular expression to find sub-string expression that will replace, 
   i.e: ' +'      (space with +) capture number of spaces.
3. second argument is what will replace in place of first argument, 
   i.e: ' '       (one single space to replace with number of spaces)
4. third argument is your piece of text variable that you want to clean.