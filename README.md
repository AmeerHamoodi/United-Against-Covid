# Welcome to UAC Computer Programming Course

# Week 1
## Lesson 1
  ### Installing python:
  - Go to the [python site](https://www.python.org/downloads/release/python-385/python-3.8.5.exe)
  - Run the installation and note the path python is installed in
  - Go to the control panel
  - Go to system & secuirty
  - Go to to system
  - On the left click advanced settings
  - Click enviroment variables
  - Select the path enviroment variable
  - Click new
  - Enter the path python was installed in
  
  ### Installing a text editor:
  - Go to the [sublime text site](https://www.sublimetext.com/) or the [notepad++ site](https://notepad-plus-plus.org/downloads/) and install the editors
  
  ### Testing python:
  - Enter `python --version` in your terminal/command prompt
  - The expected output is `Python 3.8.5` or another version
  ```terminal
  C:\Users\username>python --version
  Python 3.8.5
  ```

  ### Making your first python file:
  - Create a new folder in documents and name it something like "python-tutorials"
  - Open your editor and press Ctrl + N (or Cmd + N for mac) and naviaget to the folder you made.
  - Save the file as "first.py" **NOTE** the .py is very important.
  - Type the following code:
  
  ```python
  name = "Ameer"
  age = 16
  favouriteColourPurple = False

  print("Hello my name is " + name + " I am " + str(age) + " years old. The statement I like purple is " + str(favouriteColourPurple))
  ```
  - Edit the values of `name`, `age` and `favouriteColorPurple` to your preference.
  - To execute the file open command prompt or terminal
  - Navigate to your folder using the `cd` command (change directory)
  - Once there enter `python yourFileName.py` `yourFilename` being the name of your python file
  
  ```terminal
  C:\Users\username\Documents\pythonTutorials>python first.py
  Hello my name is Ameer I am 16 years old. The statement I like purple is True.
  ```
  
  ### Project:
  - Create a custom command line output that says your name, age and favourite color
  Example output:
  ```
  "                                           "
  " ---------- Ameers Welcome Script ---------"
  "|         My name is Ameer Hamoodi         |"
  "|            I am 16 years old             |"
  "|         My favourite color is blue       |"
  " ----------------- END --------------------"
  ```

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AmeerHamoodi/United-Against-Covid/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
