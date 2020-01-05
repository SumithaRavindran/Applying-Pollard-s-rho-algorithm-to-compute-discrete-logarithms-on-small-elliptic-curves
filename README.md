# Applying-Pollard-s-rho-algorithm-to-compute-discrete-logarithms-on-small-elliptic-curves
Rho Algorithm:
Algorithm to compute discrete logarithm problem
Idea – defining a sequence of elements that will periodically recurrent and then finding for a match in the sequence. 
The match will lead to a solution of discrete logarithm problem .

In this project, I implemented four methods such as Mul(), Exp(), Rho(), and Check().
Mul() – It multiplies two points on the elliptical curve and gives the result as a third point by making use of the formula
Exp() – It finds the value of curve point 𝑏= 𝑎^𝑚
Rho() – It recovers the value of 𝑚 and counts number of steps required to that computation. 
Check() – It generates a random exponent 𝑚 𝑚𝑜𝑑𝑢𝑙𝑜 𝑛 and computes 𝑏= 𝑎^𝑚
	using exp(), recovers the value of discrete logarithm 𝑚^′ using rho() and verifies 	if  𝑚=𝑚^′.
