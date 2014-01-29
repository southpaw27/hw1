Some Useful *nix Tools
======================

Extracting information about files
----------------------------------

### `file` - determine file fype

### `od` - octal dump

See the contents of a file (binary or otherwise).  Note that `od -a` dumps
something close to an ASCII representation.

### 'aspell' - spell checker

See whether or not there are misspellings in your file. There is a spell
checking mode that allows for in program editing of words and their correct
spellings. Also, it is possible to list all the misspelled words in a file
by using "aspell list < fileName".

### 'tr' - text manipulator

Manipulate text with different commands. Remove items with "tr -d 'item' < 
fileOriginal > fileChanged".

### 'sed' - file manipulator

Manipulate a file with this tool. For example, only print the first so many
lines of a file using "sed -n #,#"

### 'cut' - cut text out of a file

Cut works like cut in a regular text editor. It removes the text and saves
it to a paste buffer to be used later if desired. Is very useful when 
wanting to only print a certain column of a CSV file: 
"cut -f(column num wanted) -d, file"

### 'sort' - a sorter

Sort allows the sorting of the contents of a file by both numeric and 
alphabetical methods.

### 'grep' - search for certain text

Grep is a pattern matcher that will look through files to find a pattern
matching the given pattern.


