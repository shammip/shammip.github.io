## Week 1: Introduction

### Status Update

What did you do last week?
* N/A

What do you plan to do this week?
* Create a GitHub Pages website
* Write a project proposal 
* Complete LeetCode - Introduction: write notes
* Write a weekly update

Are there any impediments in your way?
* I will need to relearn HTML to create my website. 
* I will need to come up with various ideas for a project and decide on one. 

Reflection on the process you used last week, how can you make the process work better?
* N/A

### LeetCode Course Notes 

**Introduction to Big O:** 
* big O: an algorithm’s computational complexity 
* time complexity: how much time does the algorithm take? 
* space complexity: how much memory does the algorithm take? 
* constants are ignored 
* best complexity is O(1) / constant time / constant space 
* three cases: best case scenario (unlikely to use this one), average case scenario, worst case scenario
* Example #1: 
`
for (array) {		#O(n) because looping through array

	print(num)	#O(1) because printing each element in array once
	
}			#time complexity = O(1 x n) = O(n)
`

* Example #2: 
`
for (array) {					#O(n)

	for (int i = 0; i < 500,000; i++)	#O(1) = O(500,000)
	
		print(num)			#O(1)
		
}						#time complexity = O(1 x 1 x n) = O(n)
`

* logarithmic time: ex. O(log n)

**Introduction to Recursion:** 
* iterative algorithm: use for and while loops for repetition 
* Example:
`
for (int i = 1; i <= 10; i++)

	print(i)
`
		
* recursive algorithm: use function calls for repetition 
* Example:
`
function fn(i):

	if i > 10:	#base case to stop recursion 
	
		return 
		
	print(i)
	
	fn(i + 1)
	
	return
	
fn(1)
`
