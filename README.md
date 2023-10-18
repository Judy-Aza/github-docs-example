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

## Step 2 - How to take a screenshot

Taking a screenshot can vary depending on your operating system. Here are instructions for taking screenshots on some of the most common operating systems: Windows, macOS, and Linux.

**On Windows:**

1. **Capture the Entire Screen:**
   - Press the `PrtScn` (Print Screen) key on your keyboard. This captures the entire screen.
   - The screenshot is copied to your clipboard. You can paste it into an image editing program (like Paint or Photoshop) and save it.

2. **Capture the Active Window:**
   - Press `Alt + PrtScn`. This captures only the currently active window.
   - Like before, the screenshot is copied to your clipboard.

3. **Snipping Tool (Windows 7) or Snip & Sketch (Windows 10 and 11):**
   - You can use these built-in apps to take more customized screenshots. Search for them in the Start menu.

4. **Snip & Sketch Shortcut (Windows 10 and 11):**
   - Press `Windows + Shift + S` to open the Snip & Sketch tool for capturing custom areas of your screen.

**On macOS:**

1. **Capture the Entire Screen:**
   - Press `Command (⌘) + Shift + 3`. The screenshot is saved to your desktop.

2. **Capture a Custom Area:**
   - Press `Command (⌘) + Shift + 4`, then drag to select the area you want to capture.

3. **Capture a Specific Window:**
   - Press `Command (⌘) + Shift + 4`, then press `Spacebar`, and click on the window you want to capture.

**On Linux:**

1. **Using the PrtScn (Print Screen) Key:**
   - Press the `PrtScn` key to capture the entire screen. The screenshot is typically saved in your home folder or Pictures folder.

2. **Using a Screenshot Tool:**
   - Many Linux distributions come with screenshot tools. For instance, you can use "Screenshot" in Ubuntu. You can search for the screenshot utility in your application launcher or run it from the terminal.

3. **Using the Terminal:**
   - You can use the `gnome-screenshot` or `scrot` commands to take screenshots via the terminal.

The method may also depend on your desktop environment (e.g., GNOME, KDE, etc.) in Linux, as they may have their own screenshot tools.

Remember that these are general instructions, and the exact steps or keyboard shortcuts may vary slightly depending on your specific setup and any third-party software you have installed.
## Referencing
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [7 Interesting Ruby Code Examples](https://www.rubyguides.com/2019/02/ruby-code-examples/)

  ## Create a table

  | Syntax      | shortcode | Emoji|
  | ----------- | ----------- | ----------- |
  | Cloud      | `:Cloud:`     | :cloud: |
  | Cloud      | `:Cloud:`     | :cloud: |
  | Cloud      | `:Cloud:`     | :cloud: |
