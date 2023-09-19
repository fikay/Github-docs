# Github-documentation

## Step 1 - Using codeblocks.

Codeblocks are useful for **copying, pasting and sharing code.**
This is very useful for cloud engineers as it allows others to copy and paste the code for research or for replication.

### Example of a Code Block.
The syntax is highlighed due to the specifying the code's language  after the 3 back ticks
``` c#

public class Person
{
    // Properties
    public string FirstName { get; set; }
    public string LastName { get; set; }
    public int Age { get; set; }

    // Constructor
    public Person(string firstName, string lastName, int age)
    {
        FirstName = firstName;
        LastName = lastName;
        Age = age;
    }

    // Method to display information about the person
    public void DisplayInfo()
    {
        Console.WriteLine($"Name: {FirstName} {LastName}");
        Console.WriteLine($"Age: {Age} years old");
    }
}
```

Errors in the terminal are of the language type Bash. For example:
``` Bash
#!/bin/bash

# Prompt the user for their name
echo "Please enter your name:"
read name

# Greet the user
echo "Hello, $name! Welcome to the Bash scripting world."
```

## Use GFM Task List
You can create tasks in the Readme by using task lists provided by GFM.
An x marks it as completed. 
- [x] Task 1.
- [ ] Task 2

## Tables and Emoji's in GFM

| Name  | shortcode | Emoji|
| ------------- | ------------- |-------------|
| Clouds | `:cloud:` |  :cloud:   |
| Beginner  | `:beginner:`  | :beginner:    |


## References
-[Basic Writing Syntax](https://docs.github.com/en/get-started/writing-on-github)  
-[Creating Task List](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists)  
-[Emoji Cheat Sheet ](https://github.com/ikatyang/emoji-cheat-sheet)
