# week 1:

- Programming competition, testing
	1. Testing System verdicts:
		- CE (compilation error)
		- RE (Runtime error)
		- TL (Time Limit Exceeded)
		- ML (Memory Limit exceeded)
		- PE (Presentation error [output is formatted incorrectly])
		- WA (Wrong answer)
		- AC (Accepted)

		### except CE and AC, the test number is reported.

	2. Steps in problem solving:
		- Read the Statement
		- Formalize it. (A mathematical formulation of what's happening.)
		- Invent a solution:
			- Knowing different ideas in algorithm will help.
			- and experince in simple coding.
		- Prove it. (with some welll defined test cases.)
		- Test your implementation.
		- Debug if not working.
		- Submit for AC.

		## prove it 
		- Often solutions base on wrong assumpptions.
		- Both Correctness and efficiency could depend on it.
		- So if we assume anything, it must either written in the statement or proven.
		- Proving Correctness of greedy algorithm and bounds on running time in general.

		## fixing a bug
		- Say we have found a test case at which our program isn't working on.
		- An error could be on any step.
		- So we need to check all of them.
		- If we have found an error on some step then:
			1. fix it and then all following steps one by one.
		- Starting from wrong step could be disastrous.