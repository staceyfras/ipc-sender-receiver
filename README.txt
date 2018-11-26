README.txt

Name: Stacey Frasier
Email: stacey726@csu.fullerton.edu
Language: C++
How to Execute:
	>>	g++ sender.cpp -o sender
	>>	g++ recv.cpp -o recv
	>>	./sender keyfile.txt | ./recv

Extra Credit: NONE
Notes: It works on the first run, but if I try to run it again it fails: "shmget: No such file or 
	directory" on some runs, and on others "shmget: file exists". I know that means that the segment with the key couldn't be found, but not sure how to 
	solve the problem. I tried to change the path of the textfile, but to no avail.




