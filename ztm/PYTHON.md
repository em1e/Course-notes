<div align="center">

# Complete Python Developer

</div><br>

## Comparison Operators:
```python
==                      # equal
!=                      # not euqal
>                       # left is greather than right
<                       # left is less than right
>=                      # left is greather or equal than right
<=                      # left is less  or equal than right
<element> is <element>  # check if two operands refer to same object in memory
```
## Logical Operators:
```python
1 < 2 and 4 > 1    # True
3 < 2 or 4 > 1     # True
1 is not 4         # True
not True           # False
1 not in [2, 3, 4] # true

if <condition>:
  <action>
elif <condition 2>:
  <action>
else:
  <action>
```
## Numbers:
#### Types int and float:
```python
type(1)    # int
type(10)   # int
type(0)    # int
type(0.0)  # float
type(2.2)  # float
type(4E2)  # float = 4*10 to the power of 2
```

#### Aristhmetic
```python
10 + 3    # 13
10 - 3    # 7
10 * 3    # 30
10 ** 3   # 1000
10 / 3    # 3.333
10 // 3   # 3 --> floor division - no decimals and returns an int
10 % 3    # 1 -> modulo operator - return the reminder. Good for deciding if number is even or odd.
```

#### Basic Functions:
```python
pow(5, 2)         # 25 --> same as 5**2
abs(-50)          # 50
round(5.46)       # 5
round(5.468, 2)   # 5.47 --> round to nth digit
bin(512)          # '0b1000000000' --> binary format
hex(512)          # '0x200' --> hexadecimal format
```

#### Converting Strings to Numbers:
```python
age = input("How old are you?")
age = int(age)

pi = input("What is the value of pi?")
pi = float(pi)
```

## Strings:
```python
type('hellooooo world!')  # str

'I\'m thirsty'  # I'm thirsty
"I'm thirsty"
"\n"            # new line
"\t"            # adds a tab

"abcdefg"[4]    # e
abc = 'abcdefg'
abc[4]          # d
abc[:]          # abcdefg
abc[1:]         # bcdefg
abc[:1]         # a
abc[-1]         # g
abc[::1]        # abcdefg
abc[::-1]       # gfedcba
abc[0:5:2]      # ace --> starts from pos 0, ends at pos 5, steps over odds

# : is called scicing and has the format [ start : end : step]

'Hi there ' + 'Timmy'  # 'Hi there Timmy' --> This is called string concatenation
```
#### Basic Functions:
```python
len('turtle')    # 6
```
#### Basic Methods:
```python
'    I am eating alone '.strip()  # 'I am eating alone' --> takes out whitespace for both ends
'I am eating alone'.strip('e')    # 'I am eating alon' --> strips out e's from both ends
'I am alone'.split()              # ['I', 'am', 'alone']
'Join me'.replace('me, 'amy')     # 'Join amy' --> replaces first parm with second one
'I am alone'.startswith('am')     # False
'I am alone'.endswith('alone')    # True
'I am alone'.index(e)             # 1 --> counts the amount of 'e' in the string
'i am alone'.upper()              # I AM ALONE
'I AM ALONE'.lower()              # i am alone
'I am alone'.capitalize()         # I Am Alone
'I am alone'.find('a')            # 5 --> at what index does 'e' show up for the frist time
'I am alone'.count('a')           # 2

```
#### String Formatting:
```python
```
#### Palindore check:
```python
```

## Boolean:
```python
```

## Lists:
```python
```
#### Add to lists:
```python
```
#### Copy a list:
```python
```
#### Remove from list:
```python
```
#### Ordering:
```python
```
#### Useful operations:
```python
```
#### Get first and last element:
```python
```
#### Matrix:
```python
```
#### Looping through a matrix by rows:
```python
```
#### transforming into a list:
```python
```
#### List Comprehensions:
```python
```
#### Advanced Functions:
```python
```
#### Read line of a file into a list:
```python
```

## Dictionaries:
```python
```
#### Dictionary Comprehension
```python
```
## Tuples:
```python
```
#### Immutability:
```python
```
#### Methods:
```python
```
#### Zip:
```python
```
#### Unzip:
```python
```
#### Named Tuple:
```python
```
## Sets:
```python
```
## Loops:
```python
```
## Functions (**args and **kwargs):
```python
```
#### Ordering of parameters:
```python
```
#### Other:
```python
```
## Range:
```python
```
## Counter:
```python
```
## Ordereddict:
```python
```
## lambda:
```python
```
## Comprehensions:
```python
```
## Turnary condition:
```python
```
## Map filter reduce:
```python
```
## Any and all:
```python
```
## Scope:
```python
```
<!--- page 23 --->
