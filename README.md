# Shell-Script
Linux Shell Script from Basics

Linux Shell Script step by step
-------------------------------

script 1)

Print the value using echo
--------------------------
vim script1.sh

#!/bin/bash
echo "Welcome to linux shell script"

Output : Welcome to linux shell script


script 2)

vim script1.sh

#!/bin/bash
echo  "What is your name ?"
read name;
echo "HI" $name "Nice to Meet you..................."


Output : Hi ****** Nice to Meet you...................


script 3) ( \n will give blank space for next line )

vim script1.sh

#!/bin/bash
echo "What is your name ?"
read name;
echo "\n"
echo "HI" $name "Nice to Meet you..................."
echo "\n"

Output : Hi ****** Nice to Meet you...................

OR

#!/bin/bash
echo "What is your name ?"
read name;
echo "\nHI" $name "Nice to Meet you...................\n"

script 4)

vim script1.sh

#!/bin/bash
date | awk '{ print $2 $3}'

output : Sep23  

if you need space between Sep and 23, follow below script.


script 5)

vim script1.sh

#!/bin/bash
date | awk '{ print $2 " " $3}'

output : Sep 23  

script 6)

read -p 'Enter your name:' First last && echo  "\nHI" "First name is : $First " "  Last name is : $last";








