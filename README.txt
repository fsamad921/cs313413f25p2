COMP 313/413 Project 2 Report Template

TestList.java and TestIterator.java

	TODO also try with a LinkedList - does it make any difference?

    For TestIterator.java, the setup() method, both ArrayList and LinkedList implement the List
    interface, so the test results are the same. The difference is in performance: ArrayList is
    faster for access by index, while LinkedList is better for insertions and removals
    in the middle. For these small tests, there is no major difference.

TestList.java

	testRemoveObject()

		list.remove(5); // what does this method do?

			It removes any value that is at index 5.

		list.remove(Integer.valueOf(5)); // what does this one do?

			It removes the first time the number "5" appears on the list.

TestIterator.java

	testRemove()

		i.remove(); // what happens if you use list.remove(77)?

			It will try to remove the value at the 77th index, which is out of bounds.

TestPerformance.java

	State how many times the tests were executed for each SIZE (10, 100, 1000 and 10000)
	to get the running time in milliseconds and how the test running times were recorded.

	SIZE 10
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:  val1 val2 val3 val4 val5 val6  ... (fill these in in ms)
        testLinkedListAddRemove: val1 val2 val3 val4 val5 val6
		testArrayListAccess:     val1 val2 val3 val4 val5 val6
        testLinkedListAccess:    val1 val2 val3 val4 val5 val6

	SIZE 100
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:  val1 val2 val3 val4 val5 val6  ... (fill these in in ms)
        testLinkedListAddRemove: val1 val2 val3 val4 val5 val6
		testArrayListAccess:     val1 val2 val3 val4 val5 val6
        testLinkedListAccess:    val1 val2 val3 val4 val5 val6

	SIZE 1000
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:  val1 val2 val3 val4 val5 val6  ... (fill these in in ms)
        testLinkedListAddRemove: val1 val2 val3 val4 val5 val6
		testArrayListAccess:     val1 val2 val3 val4 val5 val6
        testLinkedListAccess:    val1 val2 val3 val4 val5 val6

	SIZE 10000
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:  val1 val2 val3 val4 val5 val6  ... (fill these in in ms)
        testLinkedListAddRemove: val1 val2 val3 val4 val5 val6
		testArrayListAccess:     val1 val2 val3 val4 val5 val6
        testLinkedListAccess:    val1 val2 val3 val4 val5 val6

	listAccess - which type of List is better to use, and why?

		Your answer here.

	listAddRemove - which type of List is better to use, and why?

		Your answer here.
