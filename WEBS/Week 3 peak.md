ED questions 
Q1) Insert text
touch hw.txt 
vim hw.txt
I (goes to insert)
hello world
esc
:wq


Q2) Join Lines
cp `/course/linuxgym/vimdata/wordlist.txt` ~
ls 
vim wordlist.txt
I 
fix lines
:wq


Q3) Delete a word
cp `/course/linuxgym/teeny/1mwsm10.txt` ~
ls
vim 1mwsm10.txt
6G ( takes u to line 6 )
dw (delete word)
:wq


Q4) Search and line deletion
cp yadada ~
vim yadadada
:g/opera-girls/d
:wq


Q5) Deletion by line numbers
cp yadayda
vim yadyada
:50,4049d (deletes 4000 lines)

Q6) Cut and paste by line numbers 
cp yadayadayada
vim yadayada
:1,10m$ (selects first ten then move to the bottom)

Q7) Delete to the end of a file
:1024,$d (starts at line 1024 and deletes to the end)

Q8) Search and replace strings

Q9) Search and replace words

Q10) Cut and paste by markers