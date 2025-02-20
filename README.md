# Unexpected Behavior When Assigning to Getter Methods in Ruby

This example demonstrates an often-overlooked aspect of Ruby's behavior.  When you define a getter method (like `value` in the example), directly assigning to that getter does *not* modify the internal instance variable. This can lead to unexpected results and hard-to-debug issues.  The solution below shows how to correctly implement setter methods to modify the instance variable.

This repository contains two files:

* `bug.rb`: Demonstrates the unexpected behavior.
* `bugSolution.rb`: Shows the correct way to implement setters for mutable instance variables.