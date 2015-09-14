# Java-Dumps


QUESTION: 1
Given:
1. public class Threads2 implements Runnable {
2.
3. public void run() {
4. System.out.println("run.");
5. throw new RuntimeException("Problem");
6. }
7. public static void main(String[] args) {
8. Thread t = new Thread(new Threads2());
9. t.start();
10. System.out.println("End of method.");
11. }
12. }
Which two can be results? (Choose two.)
A. java.lang.RuntimeException: Problem
B. run.
java.lang.RuntimeException: Problem
C. End of method.
java.lang.RuntimeException: Problem
D. End of method.
run.
java.lang.RuntimeException: Problem
E. run.
java.lang.RuntimeException: Problem
End of method.

Answear D,E
