# INSTRUCTIONS

To start game player will enter:
```
	start(X)
```

To respond to question player should reply back with the question number. And the parameters will
follow one of two conditions:

1. if the question number is q1:

```
	respond with q1(yes or no, Prove, ProveNegation, Answer).
	you do not need to put in anything for Prove, ProveNegation or Answer.
```

2. else:
	respond with QuestionNo(yes or no, Prove, ProveNegation, NewProve, NewProveNegation, Answer).
	Prove and ProveNegation should be filled with what is returned from the previous question,
	COPY IT AND PUT IT IN
	
 eg:	
 
 ```
 	?- q1(yes, X, Y, A).
	?- X = [something]
	?- Y = [something]
	?- A = [q2, something, something, something]
	?- q2(no, [something], [something], X, Y, A).
```
  
  In collaboration with Sophia Chen and Alice Zhu for CPSC 312 
