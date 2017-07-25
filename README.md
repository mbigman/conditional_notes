# conditional_notes
Notes on Conditional Statements

### Simple If Statement

In this section, you'll use an **if statement**. Here's the syntax:

```ruby
if condition_goes_here
  do_something_here
end
```
So the example...
```ruby
if 4 < 5
  puts "Four is less than five."
end
```
...will print the sentence "Four is less than five." to the terminal.

### If Else Statement

In the last section we wrote a simple **if statement**. Let's get a little more specific with an **if/else statement**. An **if/else statement** first checks the condition of the if statement. If that returns false, it moves onto the else statement and executes the code in that branch. In an **if/else statement**, some code will always get executed. Let's review the syntax:

```ruby
if condition_goes_here
  do_something_here
else
  do_something_else_here
end
```
For instance, this statement...
```ruby
if 6 < 5
  puts "Six is less than five."
else
  puts "Six is not less than five."
end
```
...will print the sentence "Six is not less than five."

Before you were just checking curfew, but now include an `else` condition in your code that reminds you that you're still under curfew. Remember, check out the spec to see what's expected!

### Complex Conditional

To achieve a multi-conditional checker, you will need to use an **if/elsif/else statement**. 

Here's the syntax:
```ruby
if condition_goes_here
  do_one_thing_here
elsif
  do_another_here
else
  do_something_else_here
end
```
This code...
```ruby
if 6 < 5
  puts "Six is less than five."
elsif 6 == 6
  puts "Six equals six."
else
  puts "Six is not less than five and six does not equal six."
end
```
...will print the sentence "Six equals six."

