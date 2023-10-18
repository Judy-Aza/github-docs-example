# writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown makes it *very easy* for tech people to **copy, paste, share code**.
A good Clud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their codes to replicate or to reseach issues

With cotation
'''
# Define the dimensions of the rectangle
length = 10
width = 5

# Calculate the area of the rectangle
area = length * width

# Display the result
puts "The area of the rectangle with length #{length} and width #{width} is #{area} square units."
'''

 - In order to create codeblocks in markdown you need to use three backticks (`)
 - Not to be confused with single cotation (')


with backticks
```
# Define the dimensions of the rectangle
length = 10
width = 5

# Calculate the area of the rectangle
area = length * width

# Display the result
puts "The area of the rectangle with length #{length} and width #{width} is #{area} square units."
```

- when you can you should attempt to apply syntax highlighting to your codeblocks

``` ruby
# Define the dimensions of the rectangle
length = 10
width = 5

# Calculate the area of the rectangle
area = length * width

# Display the result
puts "The area of the rectangle with length #{length} and width #{width} is #{area} square units."
```

  ![Stair Case Storage](https://github.com/Judy-Aza/github-docs-example/assets/51134112/4a5d7169-eeca-427b-8471-053cb3e24911)

- Good Cloud Engineers use codeblocks for both code and errors that appear in th econsole.

Here is an example of using a codeblock for an error that appears in bash
  ```bash
# Attempting to divide by zero
result = 10 / 0

# This line will never be reached because of the error
puts "Result: #{result}"
```
>Here is an example of using a codeblock for an error that appears in bash
>
## Referencing
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [7 Interesting Ruby Code Examples](https://www.rubyguides.com/2019/02/ruby-code-examples/)

  ## Create a table

  | Syntax      | shortcode | Emoji|
  | ----------- | ----------- | ----------- |
  | Cloud      | `:Cloud:`     | :cloud: |
  | Cloud      | `:Cloud:`     | :cloud: |
  | Cloud      | `:Cloud:`     | :cloud: |
