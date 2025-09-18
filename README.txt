COMP 313/413 Project 2 Report Template

TestList.java and TestIterator.java

	TODO also try with a LinkedList - does it make any difference?

    Both ArrayList and LinkedList implement the List interface, so the test results are
    the same. The difference is in performance: ArrayList is faster for access by index,
    while LinkedList is better for insertions and removals in the middle. For these small
    tests, there is no major difference.

TestList.java

	testRemoveObject()

		list.remove(5); // what does this method do?

			It removes any value that is at index 5.

		list.remove(Integer.valueOf(5)); // what does this one do?

			It removes the first instance of the number "5" that appears on the list.

TestIterator.java

	testRemove()

		i.remove(); // what happens if you use list.remove(77)?

			It will try to remove the value at the 77th index, which is out of bounds.

TestPerformance.java

	State how many times the tests were executed for each SIZE (10, 100, 1000 and 10000)
	to get the running time in milliseconds and how the test running times were recorded.

    **(For each test I ran, I increased the reps by 1000000)**
	SIZE 10
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:   18   29   39   51   63   73   ... (fill these in in ms)
        testLinkedListAddRemove:  15   22   26   33   42   45
		testArrayListAccess:       7   10   15   13   13   13
        testLinkedListAccess:      8   12   16   15   20   23

	SIZE 100
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:   26   46   67   84  104  123  ... (fill these in in ms)
        testLinkedListAddRemove:  17   29   30   39   45   47
		testArrayListAccess:       8   12   12   11   12   15
        testLinkedListAccess:     20   35   39   55   67   76

	SIZE 1000
								  #1   #2   #3    #4    #5    #6 	... (as many tests as you ran)
        testArrayListAddRemove:  150  291  440   578   739   873    ... (fill these in in ms)
        testLinkedListAddRemove:  17   27   28    36    47    49
		testArrayListAccess:       9   12   10    13    17    12
        testLinkedListAccess:    319  612  913  1210  1513  1806

	SIZE 10000
								  #1    #2    #3    #4    #5    #6 	... (as many tests as you ran)
        testArrayListAddRemove:  1474  2919  4419  5899  7326  8902  ... (fill these in in ms)
        testLinkedListAddRemove:  15    25    28    40    44    45
		testArrayListAccess:       8    10    11    11    11    13
        testLinkedListAccess:    4247  8433 12679 16936 21234 25142

	listAccess - which type of List is better to use, and why?

		Your answer here.

	listAddRemove - which type of List is better to use, and why?

		Your answer here.
