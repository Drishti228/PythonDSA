### Question
> Implement a Python function called print_items. This function should take a single integer as an argument and print out a sequence of numbers from 0 up to, but not including, the provided integer. The function should use a for loop and Python's built-in range function to generate the sequence of numbers. The function signature should be: def print_items(n). Example:
> Here is an example of how your function should behave:
> If you call print_items(10), your function should print:
> ![image](https://github.com/user-attachments/assets/3a1b5ce9-b4b5-43e6-ad4b-ff511b2703b8)


### Code : 
<pre>
  def print_items(n):
    for i in range(n):
        print(i)

print_items(10)
</pre>
