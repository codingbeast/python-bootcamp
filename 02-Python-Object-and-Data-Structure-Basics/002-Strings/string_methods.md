| method | description    |
| ---------|:---------|
| capitalize()| 	Converts the first character to upper case    |
| casefold()	| Converts string into lower case    |
| center(length:int, character:str)	| Returns a centered string    |
| <td colspan=2>character = replace with space, length = total length of string</td>    |
| count(value: int, start: int, end: int)| 	Returns the number of times a specified value occurs in a string    |
| string.encode(encoding=encoding, errors=errors)| 	Returns an encoded version of the string    |
| <td colspan=2>'backslashreplace'	- uses a backslash instead of the character that could not be encoded </td>   |
| <td colspan=2>'ignore'	- ignores the characters that cannot be encoded  </td>  |
| <td colspan=2>'namereplace'	- replaces the character with a text explaining the character </td>   |
| <td colspan=2>'strict'	- Default, raises an error on failure  </td>  |
| <td colspan=2>'replace'	- replaces the character with a questionmark  </td>  |
| <td colspan=2>'xmlcharrefreplace'	- replaces the character with an xml character </td>   |
| <td colspan=2>'encoding' - utf-8, ascci, example error : Ståle</td>    |
| endswith(value: str, start : int, end: int)	| Returns true if the string ends with the specified value    |
| expandtabs(tabsize : int)	| Sets the tab size of the string    |
| find(value:str, start: int, end: int)	| Searches the string for a specified value and returns the position of where it was found    |
| format(value1, value2....)	| Formats specified values in a string    |
| index(value:str, start: int, end: int)| 	Searches the string for a specified value and returns the position of where it was found    |
| isalnum()	| Returns True if all characters in the string are alphanumeric [a-z][0-9]    |
| isalpha()	| Returns True if all characters in the string are in the alphabet[a-z]    |
| isascii()	| Returns True if all characters in the string are ascii characters    |
| <td colspan=2>list : https://www.w3schools.com/charsets/ref_html_ascii.asp </td>   |
| isdecimal()| 	Returns True if all characters in the string are decimals [0-9] example number : \u0033    |
| isdigit()	| Returns True if all characters in the string are digits [0-9] example number : \u00B2    |
| isidentifier()| 	Returns True if the string is an identifier valid veriable or identifyer    |
| islower()	| Returns True if all characters in the string are lower case [a-z]    |
| isnumeric()	| Returns True if all characters in the string are numeric example ¾ not "-1" and "1.5"    |
| isprintable()| 	Returns True if all characters in the string are printable  example \n    |
| isspace()| 	Returns True if all characters in the string are whitespaces    |
| istitle() | 	Returns True if the string follows the rules of a title , all string start with Capital letter.    |
| isupper()| 	Returns True if all characters in the string are upper case    |
| join(iterable)	| Joins the elements of an iterable to the end of the string    |
| ljust(length: int, char:str)	| Returns a left justified version of the string    |
| lower()	| Converts a string into lower case    |
| lstrip(character)| 	Returns a left trim version of the string    |
| maketrans(x,y,z)| 	Returns a translation table to be used in translations x=y , z = removed    |
| translate(dict)	| Returns a translated string    |
| partition(value:str)	| Returns a tuple where the string is parted into three parts    |
| replace(old, new, count)	| Returns a string where a specified value is replaced with a specified value    |
| rfind(value, start, end)	| Searches the string for a specified value and returns the last position of where it was found, not found = -1    |
| rindex()	| Searches the string for a specified value and returns the last position of where it was found  same as rfind()    |
| rjust(length , character)| 	Returns a right justified version of the string    |
| rpartition(value:str)	| Returns a tuple where the string is parted into three parts    |
| rsplit(seprater, maxsplit)	| Splits the string at the specified separator, and returns a list    |
| rstrip()	| Returns a right trim version of the string    |
| split(separator, maxsplit)| 	Splits the string at the specified separator, and returns a list    |
| splitlines()	| Splits the string at line breaks and returns a list    |
| startswith()	| Returns true if the string starts with the specified value    |
| strip()	| Returns a trimmed version of the string    |
| swapcase()	| Swaps cases, lower case becomes upper case and vice versa    |
| title()	| Converts the first character of each word to upper case    |
| upper()	| Converts a string into upper case    |
| zfill(length: int)	| Fills the string with a specified number of 0 values at the beginning
