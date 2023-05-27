# BlockCodeHITs
# developers: 
<ul>
  <li>Name: Ivanov Vitaliy - ProNagibator2000
  <li>Subject area: Interpreter
</ul>
<ul>
  <li>Name: Seletsky Vlad - AtLeastIHaveASandwich
  <li>Subject area: UI/UX
</ul>

![123](https://github.com/ProNagibator2000/BlockCodeHITs/assets/120786249/fdd71c62-060d-45eb-b9a9-bcf105877836)

There are 4 types of variables:
<ul>
  <li>int
  <li>double
  <li>boolean
  <li>char
</ul>
There is also support for arrays consisting of elements of these types

To declare a variable, you need to specify the type and name:  
<ul>
  <li>int a
  <li>char ch
</ul>

You can also specify a non-zero starting value of the variable, for this the '=' operator is used:
<ul>
  <li>int a = 323
  <li>double b = 32.3 + (52.2 - 1.0)
  <li>boolean flag = false
  <li>char ch = 'c'
</ul>

To declare arrays, you must specify the type name and specify the number of elements inside the '[]' operator
<ul>
  <li>int a[32]
  <li>double b[10]
  <li>boolean flag[2]
  <li>char ch[45]
</ul>

In addition, an array of type char is a string, and you can assign a string to it without specifying the number of elements:
<ul>
  <li>char ch[] = "String"
  <li>char ch[45] = "Temple"
</ul>

To change the value of a variable, array element, or string value in the set block, specify its name and use the '=' operator to assign a new value to it:
<ul>
  <li>a = 32 + 3 % (3 / 2) + b - a
  <li>arr[i+1] = arr[i] + 4 - 1
  <li>str = "new string"
</ul>

To convert the variable type, you need to specify the operators toInt, .toDouble, .toBoolean or .toChar before the operand:
<ul>
  <li>a = 32.toDouble
  <li>arr[i+1] = arr[i].toBoolean
  <li>str[j] = 48.toChar
  <li>str[j] = 48.6.toInt
</ul>
