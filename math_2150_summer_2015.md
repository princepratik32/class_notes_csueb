#MATH 2150, Professor Jonathan Traugott

###Monday, June 22, 2015, 1600 - 1750

* Logic
	* Propositional Logic
		* Syntax:
			* Symbols p, q, r -> Propositions
			* True, False are propositions
		* If A & B are propositions... So are A, !A, A ^ B, A V B, A -> B, A <-> B 

	* Propositions are true or False.
		* Negation:  
			A	!A  
			T	F  
			F	T  

		* Conjunstion:  
			A	B	A ^ B  
			T	T	T  
			T	F	F  
			F	T	F  
			F	F	F  
		
		* Disjunction:  
			A	B	A V B  
			T	T	T  
			T	F	T  
			F	T	T  
			F	F	F  

		* Conditional:  
			A	B	A -> B  
			T	T	T  
			T	F	F  
			F	T	T  
			F	F	T  

		* Biconditional:  
			A	B	A <-> B  
			T	T	T  
			T	F	F  
			F	T	F  
			F	F	T  
	* Logically Equivalent sign: '=' (Actually it's 3 parallel lines) 
	* p = p ^ (p V q) Absorption 
	* Order of evaluation: !, ^, V, ->, <-> 
	* p -> (p V q) -> Always True -> Tautology 
	* p ^ !(q -> p) -> Always False -> Contradiction 
	* If neither Tautology nor Contradiction, it's Contingency 
	* Some properties:  
		A ^ T = A  
		A ^ F = F  
		A V T = T  
		A V F = A  
		A ^ A = A  
		A V A = A  
		A ->A = T  
		A ^ (B V C) = (A ^ B) V (A ^ C) -> Distribution Law  
		!(A ^ B) = !A V !B -> De Morgan Law  
