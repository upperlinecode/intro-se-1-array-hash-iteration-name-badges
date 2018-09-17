# Company Mugs

##### Arrays and Hashes

-------

### The Goal

You've just been hired at a new company called Badges. They're running an app and doing well, so there are over 200 employees with the company right now.

The holiday party is coming up, and Jose, the CEO, wants to print personalized coffee mugs for each of his employees with their first names on them.

He has an array with the first names of all the employees, but doesn't have time to do the organizing, so he's giving that task to you. Ultimately, he needs to know how many of each mug to order. For example, if there are three employees who are all named Sarah, then you'll need to order 3 mugs with the string "Sarah" printed on them.

### The Strategy

This could be a daunting task, so Jose has written out a series of increasingly challenging tasks for you and put them in a file called make_badges.rb - you can run it by typing `ruby make_badges.rb` in the console, but it won't do anything until YOU write the code.

The last task is a list of all the names and the corresponding numbers. There are about a dozen different ways you could output this information, but the most useful is probably as a hash, with the names as a strings paired to the number of mugs you need. Here's what that might look like:

```Ruby

mug_count = {
  "Virginia" => 4,
  "Jason" => 1,
  "Christine" => 3
  # Etc, until you've ordered one mug for each person in the company.
}

```
