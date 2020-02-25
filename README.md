# Code Auditor

I have a nice E-ink e-reader that I would like to use to read through code and take hand-written notes, but it is only capable of paging through simple txt and pdf documents.

So, I wrote this bash script to generate large txt and pdf files to make it easy to read through code using resources from here:
https://unix.stackexchange.com/questions/46276/finding-all-non-binary-files/46290#46290

and here:
https://www.unix.com/shell-programming-and-scripting/204319-recursively-cat-files-directory-filename-printed-first.html

# Running
run genaudit.sh on a directory and it will recursively print all contents of all text/code files (ignoring binary files) to a file named allcode.txt. It will also generate a file named allcode.pdf

# Other uses
If you need to print out your code for compliance reasons, or would like to page through a lot of code in your favorite terminal program or text editor very quickly

