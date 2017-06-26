# Python Review
The following review notes are compiled based on [Google for Education's Python resource](https://developers.google.com/edu/python/)


### Python Introduction/General
#### General Structure

```python
#!/usr/bin/env python

# import modules
import sys

# main function
def main():
    print 'Hello there', sys.argv[1]
    # Command line args are in sys.argv[1]
    
# Standard boilerplate to call the main() function to begin the program.
if __name__ == '__main__':
    main()
```

#### User Defined Functions
```python
def function(var1, var2):
    #____function code____
    
    return var1, var2
```

#### Python Standard Library
These are common packages:
* sys - access to exit(), argv, stdin, stdout, ...
* re - regular expressions
* os - operating system interface, file i/o

For all packages, refer to [Python Library](http://docs.python.org/library)

### Python Strings
* Python's built in string class -> str
* Strings are immutable
* Characters in a string accessed using "[]" syntax (Same way you manipulate lists)

Example:
```python
name = "eric"
print name[1]   --> r
print len(eric) --> 4
print name + "is awesome" --> eric is awesome
```

### String Methods
Link: https://docs.python.org/3/library/stdtypes.html#string-methods

* s.lower(), s.upper() --> lower and upper case
* s.strip() --> returns a string with whitespace removed
* s.isalpha, s.isdigit. s.isspace() --> tests if strings are the various scenarios
* s.startswith, s.endswith()
* s.find()
* s.replace()
* s.split()
* s.join(list)

### String Slices
Slice and dice a string as if it were a list


_....To be continued_






