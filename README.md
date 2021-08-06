2nd Day-
1st Problem:
https://leetcode.com/problems/valid-palindrome/submissions/

2nd problem: 
https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/submissions/

Python OOP
Class
A class is a blueprint for the object.

class Parrot:
    pass
Object
An object has two characteristics:

attributes
behavior
Let's take an example:

A parrot is an object, as it has the following properties:

name, age, color as attributes
singing, dancing as behavior
class Parrot:

    # class attribute
    species = "bird"

    # instance attribute
    def __init__(self, name, age):
        self.name = name
        self.age = age

# instantiate the Parrot class
blu = Parrot("Blu", 10)
woo = Parrot("Woo", 15)
Mutable and Immutable in Python
Mutable Definition
Mutable is when something is changeable or has the ability to change. In Python, ‘mutable’ is the ability of objects to change their values. These are often the objects that store a collection of data.

Immutable Definition
Immutable is the when no change is possible over time. In Python, if the value of an object cannot be changed over time, then it is known as immutable. Once created, the value of these objects is permanent.

Palindrome
A palindrome is a word, number, phrase, or other sequence of characters which reads the same backward as forward, such as madam or racecar. There are also numeric palindromes, including date/time stamps using short digits 11/11/11 11:11 and long digits 02/02/2020. Sentence-length palindromes ignore capitalization, punctuation, and word boundaries.

s = 'maddam'
start = 0
end = len(s) - 1

while start < end:
    if s[start] != s[end]:
        return False
    start += 1
    end -= 1
return True
