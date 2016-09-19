#Meta characters

##a.c -> matches axc,abc, not ac , not axxc, 
**.** matches any single character

##\ -> removes special meaning 
**/a\.c/ matches a.c**<br>
**/a\\c/ matches a\c**<br>
**/a\/c/ matches a/c**<br?


<br>
#^ & $ match line Begin & End
#[] matches any single character in set 
For Eg.: /a[xyz]b matches axb
