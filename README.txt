For TestIterator.java, the setup() method, both ArrayList and LinkedList implement the List
interface, so the test results are the same. The difference is in performance: ArrayList is
faster for random access (get by index), while LinkedList is better for insertions and removals
in the middle. For these small tests, there is no major difference. However, ArrayList was
slightly faster.


