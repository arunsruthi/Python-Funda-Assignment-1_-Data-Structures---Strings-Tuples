Link::https://colab.research.google.com/drive/1y2q86IPZYM2XftvZknQpe98QoN354oXe?usp=sharing<br><br>
**Python-Funda-Assignment-1_-Data-Structures---Strings-Tuple**<br><br>
<b>A **string**</b> in Python is an ordered, immutable sequence of characters enclosed in single quotes ('...'), double quotes ("..."), or triple quotes ('''...''' / """...""" for multi-line text).<br><br>
**String concatenation** is the process of joining two or more strings end-to-end into a single string.<br><br>
1. Using the + Operator<br><br>
   Indexing accesses a single character by its position, while slicing extracts a substring (a range of characters) from a string.<br><br>
**Indexing (Single Character)**<br><br>
Python strings use 0-based indexing from the left (0, 1, 2...) and negative indexing from the right (-1, -2, -3...):<br><br>
Index:    0    1    2    3    4    5<br><br>
String: [ 'P'  'y'  't'  'h'  'o'  'n' ]<br><br>
NegIdx:  -6   -5   -4   -3   -2   -1<br><br>
**Slicing ([start : stop : step])**<br><br>
Slicing returns a new string starting at start (inclusive) and stopping right before stop (exclusive), moving by step:<br><br>
**String methods** are built-in functions attached to string objects (string.method()) that let you inspect, transform, search, split, or format text. Because strings are immutable, every string method returns a new string (or a list/boolean/integer) without changing the original string in place.<br><br>
text = "python Programming"<br><br>
print(text.lower())       # "python programming" (all lowercase)<br><br>
print(text.upper())       # "PYTHON PROGRAMMING" (all uppercase)<br><br>
print(text.capitalize())  # "Python programming" (first char upper, rest lower)<br><br>
print(text.title())       # "Python Programming" (first char of each word upper)<br><br>
print(text.swapcase())    # "PYTHON pROGRAMMING" (inverts case)<br><br><br>
**Tuple**<br>
A tuple in Python is an ordered, immutable collection of items, typically written inside parentheses (...). Once a tuple is created, you cannot change, add, or remove its elements—making it great for fixed records or data that shouldn't be accidentally modified.


   
