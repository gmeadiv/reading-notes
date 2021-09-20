# the_coders_computer
Notes for Lesson 2

## Choosing a Text Editor
### Features to look for:
1. code completion
2. syntax highlighting
3. variety of themes
4. healthy selection of extensions

## The Command Line
## Basic Navigation
* PWD = Print Working Directory (where am i?)
* LS = List (what is here?)
 * -L = long listing
 * (-) for normal files
 * (d) for directory
 * /etc = don't list current directories *instead* list that directory's contents
* Path = how to get from here to there
  * Absolute specifies a location in relation to the root directory (always begins with /)
  * Relative specified a location in relation to where i currently am (does *not* begin with a /)
  * ~ (tilde) is a shortcut for my home directory
  * . (dot) is a reference to my current directory
  * .. (dotdot) is a reference to the parent directory
* CD = Change Directory (gets me from here to there)
  * Tab Completion = auto complete
* Touch = create a new file
* MKIR = Make directory

## More About Files
* Quotes: anything inside is considered a single item
* \ (backslash): nullifies the meaning of the next character
* Hidden files and directories
  * if file or directory name begins with "." (dot) then it is hidden
  * LS command will not reveal hidden files unless modified by including command line option "-a"
