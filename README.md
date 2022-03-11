# CS558 Lab
## How to compile and run
The code was written in Rust. Clone the repo and enter the command 'cargo run' while in the repo root directory to execute the code.
## Choosing a queue implementation
<pre><code>     const QUEUE_INT_TEST: bool = true;
  const QUEUE_STRING_TEST: bool = true;
const LINKEDLIST_INT_TEST: bool = true;
</code></pre>
At the top of main.rs are flags that control which queue is being tested. They are all 'true' by default. To select a specific test, change the rest to false.
## Code fails  

* As I've never used a functional programming language before, aside from changing the Scala code, most of my time was spent learning Rust. I was able to code the Queue to handle a generic data type and test it with integers and strings. The Linked List only handles integers and I've run out of time to work on it.

* The interface and the testing is contained within a single .rs file rather than seperately. The tests simply print a status of the queues rather than using the assert system. Again, I ran out of time to learn and implement proper tests.

* I did not find any limitations in the language for implementing these queues. Although I ran into problems with they generic Type and the String class. I think this has something to do with the borrowing and copying of values, but not sure, and didn't know how to correct it. I could only implement the Queue using &str, string literals. 


