# Methods
Methods, similar to functions in other languages, are one of the foundational
building blocks in programming. Almost every language implements some way of
making methods.

You will often find yourself writing the same code in different places in your code.
Wouldn't it be great if there was a way to reuse the same code over and over again 
without having to write it all out again? 

This is what methods are for. They allow you to wrap code in a name which you
can then use where you need that code to be run in your programs.

In this lesson we will dive deep into methods.

## Learning outcomes
*Look through these now and then use them to test yourself after doing the assignment*

* Create a new method
* Understand the syntax of a method: 'Object.method'
* Learning outcome 3
* 

### Some examples
Ruby has some built-in methods included into its library. Some of them are very straight-forward and easy to learn. Others will take more time to discover.

```ruby
"It's Peanut Butter Jelly Time!".length  # => 29
```

* We apply the `.length` method on the string "It's Peanut Butter Jelly Time!".
* `.length` counts each character within the string; this includes whitespaces.

You also have the option to create your own methods. The `.count_words` method below 

```ruby
def count_words(sentence)
  sentence.split.length
end

count_words("It's Peanut Butter Jelly Time!") #=> 5
```

* `count_words(sentence)` takes an argument and then references it inside its method.
* Then the `.split` method is called onto `sentence` followed by the `.length` method.
* `"It's Peanut Butter Jelly Time!".split` # => ["It's", "Peanut", "Butter", "Jelly", "Time"]
* 

```
def first_name(full_name)
  full_name.split[0]
end
```

### Methods Basics
- the three parts of a basic method
  - method definition
  - method body
  - closing end
- the definition is where you name it, give it a good descriptive name. Describe either what the method will output of what behaviour it has
- the method body is where the code you want to reuse goes
- the `end` marks the end of the method

There are three basic parts of a method. We will go through each using the following
example method:

```ruby
def my_name
  "John Smith"
end
```

1. The first line `def my_name` is the method definition. The keyword `def` stands
   for define, `my_name` is the name of the method. You can name your methods whatever you want but its a good idea to give methods a descriptive name which will describe what the method outputs or its behaviour as this will make it easier for other programmers and in many cases yourself to understand what the method is doing.

2. The closing `end` marks the end of the method.

3. Everything in between the first `def` line and the last `end` line is the **method body**. This is where the logic of
   your method goes. Therefore the second line `"John Smith"` is within the method body.  Your method body can conist of as many lines as you wish. But its a good idea to keep your methods as short as possible so you or another programmer can easily grasp what the method is doing. 

### Methods with Arguments

+arguments in general
?splat
+named arguments
?implicit hash at end
- method scope

### Return values
- explicit with the return keyword
- implicit (last line evaluated)
- difference between puts/print and return (beginner checks their work with puts all the time, but the computer is interested in the return not the puts)

### Calling methods
- calling methods on an object 
- calling your own methods


## Exercises
A group of exercises (If Applicable) for the student to complete in relation to the topic taught in the lesson.

## Additional Resources
*This section contains helpful links to other content. It isn't required, so consider it supplemental for if you need to dive deeper into something*

Link to no more than three additional resources to avoid this section becoming too cluttered.
