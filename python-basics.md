# Basics of Python Programming

Python has a lot of vocabulary to remember. It is critical to be able to "talk code" with other developers and to understand the problems you're facing. Learning these will help a lot!

### Types
There are three rough types that we have covered so far. They are:
-    Number - 8 is an *integer* and 7.4 is a *float*. *Floats* have decimal points, while *integers* do not.
-    String - "Matt" or "Hello", REMEMBER: strings have *quotes* around them, either single '' or double ""
-    Boolean - either True or False

### Assignment versus Equality
A SINGLE equals sign in Python is used to ASSIGN something to a variable. For example, when we say:

```python
my_float = 8.6
my_boolean = True
```

we are ASSIGNING to the variables `my_float` and `my_boolean` values. These variables can have any name, and will hold the value later, so we can use it, like this:

```python
print my_float # 8.6
print my_boolean # True
```

The DOUBLE equals sign in Python is used to check EQUALITY. This will give us a BOOLEAN value in exchange. For example:

```python
8 == 8 # True
7 == 9 # False
```

The difference is important! Remember, SINGLE ASSIGN, DOUBLE EQUALITY.

### Lists versus Dictionaries
Think of a list as a long numbered list. They are indexed by NUMBER, and that number starts at ZERO. For example

```
0.) 98
1.) 45
2.) 21
3.) 45
```

The values we store in here can be any of the types we talked about! If we want to make this list in python we can create it like so:

```python
my_list = [98, 45, 21,45]
```
If we want to access one of these values, we can use the number in SQUARE BRACKETS:

```python
my_list[0] # 98
my_list[1] # 45
```

A dictionary, however, uses KEYWORDS. Think that for every KEY, we have a VALUE. Like this:

```python
"my_favorite_fruit" => "Apple"
"my_age" => 20
"is_boy" => True
```

The VALUES can be any of our types, but our KEYS must be STRINGS.

To create this in Python, let's do the following:

```python
my_dict = {"my_favorite_fruit" : "Apple", "my_age": 20, "is_boy": True}
```

To access, we use our KEY. For example:

```python
my_dict["my_favorite_fruit"] # "Apple"
my_dict["my_age"] # 20
```

Remember:
    -   LISTS use NUMBERS and SQUARE BRACKETS
    -   DICTIONARIES use STRINGS and CURLY BRACKETS




