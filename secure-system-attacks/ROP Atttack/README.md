Here are the steps to run the exploits (Both part contains safe exit).

PART1:

1. Write the exploit string from the py file to a text file-
    python exploit1.py > e1.txt

2. Run the exe file by giving the above text file as parameter-
    ./lab_2_rop < e1.txt

		or 

1. Run directly by running the script
 
	 python exploit1.py | ./lab_2_rop

PART2:
1. Provide the key and text string in exploit2.py file- in the top part (length will be computed automatically)
    ex. key = 12
        text= "ABCD"

2. Write the exploit string from the py file to a text file-
    python exploit2.py > e2.txt

3. Run the exe file by giving the above text file as parameter-
    ./lab_2_rop < e2.txt
		
		or 
		
2. Run directly by running the script
 
	 python exploit2.py | ./lab_2_rop
