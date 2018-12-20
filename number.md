## Min and Max of numbers
- Java
```
int min = Integer.MIN_VALUE;
int max = Integer.MAX_VALUE;
```
- C#
```  
int min = int.MinValue;
int max = int.MaxValue;
```
- Python
```
min = -2^(n-1) 
max = 2^(n-1) - 1.

# python 2

>>> sys.maxint
min =  -sys.maxint - 1
```
- JavaScript
// JavaScript use float numbers
```
var max = Number.MAX_VALUE;
var min = Number.MIN_VALUE;

```




## Convert string to number
- Java
```
  int num = Integer.parseInt(t)
```
- C#
```  
  int x = Convert.ToInt32(TextBoxD1.Text)
```
- Python
```
  str_a = '50'
  c = int(str_a)
  
  str_a = '50.85'
  c = float(str_a)

```
- JavaScript
```
  var text = '42px';
  var integer = parseInt(text, 10);

  var text = '3.14someRandomStuff';
  var pointNum = parseFloat(text); // returns 3.14

  Number('123'); // returns 123
  Number('12.3'); // returns 12.3
  Number('3.14someRandomStuff'); // returns NaN
  Number('42px'); // returns NaN

```




## Number to string
- Java
```
  String s = 100 + "";
```
- C#
```  
  String s = var.toString();
```
- Python
```
  a = 50.85
  str_a = str(a)

  '{:06.2f}'.format(3.141592653589793)
```
- JavaScript
```
  // using different bases
  var num = 15;
  var a = num.toString();
  var b = num.toString(2);
  var c = num.toString(8);
  var d = num.toString(16);
```