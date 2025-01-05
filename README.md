# Ruby Type Error Example

This repository demonstrates a common type error in Ruby where an arithmetic operation is performed on a variable that may not always be a number.  The `bug.rb` file contains the erroneous code, while `bugSolution.rb` provides a corrected version.

The core issue is a lack of type checking or input validation.  The `method1` method assumes that `@value` is always a number, leading to a runtime error if it receives a different type of data, such as a String.