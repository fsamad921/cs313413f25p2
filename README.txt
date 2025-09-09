For TestIterator.java, the setup() method, both ArrayList and LinkedList implement the List
interface, so the test results are the same. The difference is in performance: ArrayList is
faster for random access (get by index), while LinkedList is better for insertions and removals
in the middle. For these small tests, there is no major difference. However, ArrayList was
slightly faster when I ran the test multiple times.

TODO Question: What happens if you use list.remove(Integer.valueOf(77))?
When trying to do this approach, it actually has a hard time running the test and threw an
exception, taking much longer than the given code we have already. I tried running the
i.remove which was much quicker and then the list.remove(Integer.valueOf(77)) which was much
slower and eventually I cancelled running the test because of how long it was taking.