##sed 's/old/new/' file

reads from file and outputs to stdout

1) sed invokes the sed program <br>
2) s specifies sed's s(substitute) command <br>
3) old and new are the search and replace string respectively <br>

We can also use multiple files and they will be read in order

##sed 's/old/new/' file1 file2 file3


##sed 's/old/new/' 
this take the input from standard input, omit files 


##sed "s/were/\"\$weren't\"/" file
using sed with command line special characters and double quotes 
use backslash to escape

#By default the sed command only effects the first occurence
How to cover all the occurence ?
## sed 's/aba/---/g'
# g modifier is not recursive

#How to modify the nth occurence
## sed 's/the/THE/2' fille

# Slashes doen't need to be slashes, it can be anything as long as the three are same
## sed 's;the;THE;g' file
### Good usage will be in example like this **sed 's;half;1/2;g' file** 
