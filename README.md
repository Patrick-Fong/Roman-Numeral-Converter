# Case Study - Roman Numeral Converter

This is a simple roman numeral converter to convert a number into a roman numeral, or vice versa. The max convertable number is set to be 3999.
Vue is used for the development.
This application was tested on Chrome version 102.0.5005.63

> **Note:** Vue is used without build tools. Internet connection is needed for  using the source: https://unpkg.com/vue@3

## Instruction

1. Download ZIP from github
2. Unzip the downloaded file
3. Open "index.html"
4. The page entered 3999 as input by default, and set to "Number to Roman" mode
	+ Click "NUMBER -> ROMAN" or "ROMAN -> NUMBER" to switch between the two mode
	+ In "NUMBER -> ROMAN", the input box only allows numeric input
	+ In "ROMAN -> NUMBER", the input box only allows roman numeral characters
	+ If the input is invalid, 😐 is shown as the result

> **Note:** 
> + Althought an input filter is placed, user can bypass the filter by drag-and-droping or copy-and-pasting string into the input box. In this case, the input is still detected as invalid.
> + The max value is set to 3999 because from 4000 on, it is more common to use roman numeral I̅V̅ instead of MMMM. The current version of converter does not support entering a vinculum over the roman numeral, so it would make more sense to limit number to roman conversion too.
