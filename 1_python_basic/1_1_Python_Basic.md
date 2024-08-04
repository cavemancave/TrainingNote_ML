## python introduce
python is an 
*interpreted*, no compile process
*interactive*, can execute code after python prompt  `>>>`
*object-oriented*, support class
*friendly*, simple for beginner, but also very powerful and widely used

## variable type
bool Ture, False
int -100
long 1000000000000L
float -1.0001
string 'hello'
list [1,2,3]
dict {'man':2, 'women':3}
tuple ('abc', 1000)
set {1,2,3}

can use type() function get variable type
a=1
type(a)
int

### operation
- `()`
- `**` power
- `* / // %` multiple, divide, floor division, mod
`+ - `
division always return float, float also can calculate power, floor divison, mod
```python
>>> 8 / 5
1.4
>>> 12.3 // -4
-4.0
```
simple math function
abs(), round(), min(), max()

other representation way than decimal
1e-6, 0xF3, 0b11110011

### bool
<, >, <=, >=, ==, !=
and or not 
support chian compare  1 < x < 10

### string
' and " is equal
''' for multiline string
+ support plus
index  s='hello' s[0]='h' s[-1]='o' s[0:5]='hello'
split s='he llo' s.split() = ['he','llo']
len  len(s)=5

### type conversion
print(str(1))  '1'
print(int('1')) 1

