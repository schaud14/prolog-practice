CS571
Programming Languages
Assignment 5:

Group Members:
1. Saurabh Chaudhari
	email address: schaud14@binghamton.edu
	section : 02

2. Aniket Rajmane
	email address: arajman1@binghamton.edu
	section : 02

Files:  1. assignment5.P
		2. assignment5.pdf
		3. README.txt

Testing:
	This Program is tested on bingsuns and working fine.
	The function names and input parameters are same as metioned in the assignment question


Description:

To run code:
	1. Type "xsb" on bingsuns after navigating to dkirectory
	2. execute "[assignment5]."
	3. Give queries as mentioned in assignment discription. 


Question 1:
	
		Sample Run:
		
		| ?- max([1,3,5,4,2], Res).

		Res = 5.

		no



Question 2:
		Sample Run:

		| ?- insertNTerm(3,f(2,3,4,5,6,7,8),Res).

		Res = f(2,3,4,1,5,6,7,1,8).
	
		no


Question 3:
		In this question we have used findall/3 build-in method to wrap results in single list.

		Reference used:
		http://cs.union.edu/~striegnk/learn-prolog-now/html/node96.html

		Sample Run:

		| ?- sublist([1,2,3],Res).

		Res = [[1,2,3],[1,2],[1,3],[1],[2,3],[2],[3],[]];

		no


Question 4:
	
		Sample Run:

		| ?- position(1, [1,3,1,2,5,1], Res).

		Res = [1,3,6].

		no


Question 5:

		Sample Run:

		| ?- merge([1,3,4,6],[2,3,5],Res).

		Res = [1,2,3,3,4,5,6].

		no

