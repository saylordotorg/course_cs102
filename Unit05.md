**Unit 5: Recursion** <span id="5"></span> 
*Often considered one of the more conceptually difficult concepts within
the field of Computer Science, recursion - the act of a function
invoking itself - is a powerful and relevant tool for any Computer
Scientist. In this unit, we will take an in-depth look at recursion,
learning the recursive steps, the role that recursion plays in common
data structures, and what happens inside the computer when a recursion
function is invoked. By the end of this unit, you will recognize
situations that require recursion and be able to apply it
appropriately.  
  
 Note: Recursion can be a difficult concept for some students new to the
field of Computer Science. This anxiety is best resolved through the use
of an example. For this module, we will employ the use of recursion to
write a program to express the “factorial” function. This
straight-forward example will give the student an overview of all the
major components of recursion.*

**Unit 5 Time Advisory**  
This unit should take you 14.5 hours to complete.  
  
 ☐    Subunit 5.1: 7 hours  
  
 ☐   Subunit 5.2: 7 hours  
  
 ☐    Assessment: 0.5 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Demonstrate an understanding of the general uses of recursion in
    programming, including its utility in solving programming problems;
    and
-   Demonstrate an understanding of the basic search algorithms that are
    recursive in nature and how they are used in programming.

**5.1 Definition** <span id="5.1"></span> 
-   **Reading: University of Ottawa: Robert C. Holte’s “Recursive
    Definitions”**
    Link: University of Ottawa: Robert C. Holte’s [“Recursive
    Definitions”](http://webdocs.cs.ualberta.ca/~holte/T26/rec-defs.html)
    (HTML)  
      
     Instructions: Read this webpage for a solid overview on recursion,
    its role in programming, and everyday examples of recursion.  This
    reading covers Subunit 5.1.1 and Subunit 5.1.5.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.1 Divide and Conquer** <span id="5.1.1"></span> 
-   **Reading: University of Ottawa: Robert C. Holte’s “Using Recursion
    to Solve Problems”**
    Link: University of Ottawa: Robert C. Holte’s [“Using Recursion to
    Solve
    Problems”](http://webdocs.cs.ualberta.ca/~holte/T26/rec-pb-solving.html)
    (HTML)  
      
     Instructions: Read this webpage for a solid overview on recursion,
    its role in programming, everyday examples of recursion, and how
    recursion can be used to solve problems.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.2 Applications to Programming** <span id="5.1.2"></span> 
-   **Reading: University of Ottawa: Robert C. Holte’s “Recursion as a
    Programming Technique”**
    Link: University of Ottawa: Robert C. Holte’s [“Recursion as a
    Programming
    Technique”](http://webdocs.cs.ualberta.ca/~holte/T26/rec-prog-tech.html)
    (HTML)  
      
     Instructions: Read this webpage for a solid overview on recursion
    and how it is used as a programming technique. This material also
    covers Section 5.1.3.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.3 Recursive Structure** <span id="5.1.3"></span> 
-   **Lecture: Massachusetts Institute of Technology: Eric Grimsom and
    John Guttag’s “Divide and Conquer Methods”**
    Link: Massachusetts Institute of Technology: Eric Grimsom and John
    Guttag’s [“Divide and Conquer
    Methods”](http://www.youtube.com/watch?v=TalbGDwsGVA) (YouTube)  
      
     Also available in:  
     [Adobe Flash, PDF Transcript, Mp4
    Download](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/video-lectures/lecture-10/)  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.2394447485.02394447490.2371004168?i=2006815686)  
      
     Instructions: Watch this 46-minute lecture on the nature of
    recursive structure. Specifically, this lecture explains the theory
    of divide and conquers algorithms.  
      
     Terms of Use: Eric Grimson and John Guttag, Introduction to
    Computer Science and Programming, Fall 2008. (Massachusetts
    Institute of Technology: MIT OpenCourseWare), http://ocw.mit.edu
    (Accessed September 21, 2011). License: [Creative Commons BY-NC-SA
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/).  The
    original version can be
    found [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/video-lectures/lecture-10).

**5.1.4 Steps** <span id="5.1.4"></span> 
-   **Reading: Saint Vincent College’s *Tutorial on Recursion*:
    “Software Design Using C++: Recursion”**
    Link: Saint Vincent College’s *Tutorial on Recursion*: [“Software
    Design Using C++:
    Recursion”](http://cis.stvincent.edu/html/tutorials/swd/recur/recur.html)
    (HTML)  
      
     Instructions: Click on the link above and read the webpage text.
    This link describes the recursion process and discusses the base
    case or stopping case that stops the recursive procedure. The
    article discusses recursive functions for factorial and Fibonacci
    numbers as well as recursive sorting algorithms such as merge sort
    and quick sort. Note that this reading will cover the material you
    need to know for Subunit 5.1.4.1 and Subunit 5.1.4.2.  
      
     Reading this tutorial should take approximately 2 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.4.1 Base Case** <span id="5.1.4.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
5.1.4.  In particular, pay attention to the base case, which is referred
to as “stopping case” in the reading.  You will learn that base case is
required in a recursive function; otherwise, the recursion will go on
forever.*

**5.1.4.2 Recursive Step** <span id="5.1.4.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
5.1.4.  In particular, pay attention to the fact that in recursive
function call, the function calls itself, but with different parameters.
 This chain of recursive calls goes on until the base case is reached. 
At this point, the recursion ends and returns the computed value.*

**5.1.5 Recursion Examples** <span id="5.1.5"></span> 
-   **Web Media: YouTube: TheNewBoston’s “Bucky’s C++ Programming
    Tutorials - 31 - Recursion”**
    Link: YouTube: TheNewBoston’s [“Bucky’s C++ Programming Tutorials -
    31 - Recursion”](http://www.youtube.com/watch?v=4agL-MQq05E)
    (YouTube)  
      
     Instructions: Watch this 10-minute video on how a recursive
    function is written. It demonstrates recursive function for finding
    the factorial of a number. To better understand this material, write
    this program in your computer using C++ and compile it. After
    successful compilation, run this program.  
      
     Watching this video and writing this program should take
    approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Khan Academy’s “Recursive Factorial Function”**
    Link: Khan Academy’s [“Recursive Factorial
    Function”](http://www.youtube.com/watch?v=7NVdL43sixg&feature=youtu.be)
    (YouTube)  
      
     Instructions: Watch this video, as the instructor explains the
    recursive factorial function in Python programming language.  
      
     Watching this video should take approximately 5 minutes.  
      
     Terms of Use: This video is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to the Khan Academy.

-   **Lecture: Khan Academy’s “Exercise - Write a Fibonacci Function,”
    “Iterative Fibonacci Function Example,” “Stepping through Iterative
    Fibonacci Function,” “Recursive Fibonacci Example,” and “Stepping
    through Recursive Fibonacci Function”**
    Link: Khan Academy’s [“Exercise - Write a Fibonacci
    Function”](http://www.youtube.com/watch?v=3QxHo_0QB_8&feature=youtu.be),
    [“Iterative Fibonacci Function
    Example”](http://www.youtube.com/watch?v=HLHxEJr8lgs&feature=youtu.be),
    [“Stepping through Iterative Fibonacci
    Function”](http://www.youtube.com/watch?v=sf3DTnKhILc&feature=youtu.be),
    [“Recursive Fibonacci
    Example”](http://www.youtube.com/watch?v=dLa-BLCyenI), and
    [“Stepping through Recursive Fibonacci
    Function”](http://www.youtube.com/watch?v=8Iy_82smrh4) (YouTube)  
      
     Instructions: Watch the lecture on Fibonacci numbers (4 minutes).
    In this series of short lectures, we’ll examine recursion by going
    through the stages of the programming process to implement a
    recursive function. Briefly, a recursive function is a function that
    calls itself.  
      
     In the Khan lectures we use Python, which is an easy-to-use
    procedural and object-oriented language, but our focus will not be
    on the syntax of the language. Rather, our focus is the concept of
    recursion, the requirements for the program (i.e., the statement of
    the problem), the design of the program, the semantics of the
    program (this is the stage in which we don’t worry too much about
    the syntax of Python - knowing Java and C++ enables you to learn
    Python easily), and the verification of the program implementation
    (we do this by stepping through the program and running several test
    cases).  
      
     Computer science and programming have strong ties with mathematics,
    and recursion may remind you of a proof method in mathematics called
    mathematical induction, which is typically used when we want to
    prove a statement involving the natural numbers, i.e., “n.” To prove
    the statement involving “n,” we: 1) prove the statement for a base
    case, usually n = 1; 2) assume the statement is true for n-1; 3)
    then prove the statement for “n,” using steps 1 and 2. So, get
    started, and watch the first video, which gives the requirements for
    the program to be written.  
      
     Then, watch the second lecture (7 minutes), which uses an iterative
    design to satisfy the requirements. Remember that this subunit is on
    recursion. So why do we look at iteration?  We use an iterative
    example to help us better understand recursion, to show that
    requirements (or programming problems) can have several program
    implementations, and to enable you to compare iteration and
    recursion. This design makes use of a list data structure. After
    implementing an iterative design, (i.e., writing the progam), Khan
    runs it to demonstrate that it works correctly for several test
    cases.  
      
     Next, watch the third lecture (10 minutes), which presents some
    verification of the iterative design by stepping through the program
    implementation, line by line and variable by variable.  
      
     Next, watch the fourth lecture (8 minutes), which now uses a
    recursive design to satisfy the requirements. This recursive
    implementation uses a string data structure to print out the
    successive calls of the function to itself. This recursive
    implementation is tested using several inputs. Note that the calls
    show that the call for “n” makes use of the call for “n-1,” etc.
    (i.e., the mathematical inductive step 2 above).  
      
     You should compare this recursive implementation with the iterative
    implementation. If you have to find a series of natural numbers, and
    you are given the first two (called the base cases) as well as the
    rule for calculating the next integer in the series, you can apply
    the rule sequentially, finding the third, the fourth, the fifth,
    etc., until you find the nth. A program that implements this manual
    approach is the iterative program; such an approach needs a data
    structure to store all the integers up to the nth one.  
      
     Another approach assumes that we can express the rule as a formula.
    For example, the nth term = (n-1)st term + (n-2)nd term; this can be
    expanded to, nth term = (n-2)nd term + 2\* (n-3)re term + (n-4)th
    term; and this expansion can be continued to result in as many terms
    as needed to give an expression that calculates the nth term. To
    find the nth term, all you would have to do is enter the base cases
    into the formula and do one calculation (no iterating). The
    recursive function, in effect, does this. The general formula is
    programmed: fibonacci (n) = fibonacci (n-1) + fibonacci (n-2). This
    general recursive formula is automatically calculated for us by the
    interpreter. The interpreter uses an internal data structure, a
    stack, to implicitly calculate the formula by “iterating” through
    the stack- i.e., the interpreter does the iteration for us.  
      
     Finally, watch the fifth and last lecture (8 minutes), which
    presents some verification of the design and implementation by
    stepping through the program, line by line and function call by
    function call. We say “some” because there are other verification
    techniques that can be used, depending on how much assurance is
    needed for correct execution of the program to satisfy various users
    and various needs.  
      
     Watching the lectures and taking notes should take approximately 50
    minutes to complete.  
      
     Terms of Use: These videos are licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  They
    are attributed to the Khan Academy.

**5.2 Recursive Algorithms** <span id="5.2"></span> 
-   **Reading: Old Dominion Univeristy: Shunichi Toida’s “Recursive
    Algorithm”**
    Link: Old Dominion Univeristy: Shunichi Toida’s [“Recursive
    Algorithm”](http://www.cs.odu.edu/~toida/nerzic/content/recursive_alg/rec_alg.html) (HTML)  
      
     Instructions: Read this webpage for an introduction on recursive
    algorithms.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: Stanford University: Julie Zelenski’s “Thinking
    Recursively”**
    Link: Stanford University: Julie Zelenski’s [“Thinking
    Recursively”](http://www.youtube.com/watch?v=uFJhEPrbycQ)
    (YouTube)  
      
     Also available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/itunes.stanford.edu-dz.4331558230?i=1819409337)  
      
     Instructions: Watch Lecture 9 for a detailed explanation on
    recursive algorithms and how to apply recursion to various
    algorithms. The examples and patterns presented include recursive
    tree calls, towers of Hanoi, and permutations.  
      
     Watching this lecture should take approximately 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**Unit 5 Assessment** <span id="5.3"></span> 
-   **Assessment: Washington University in St. Louis: Kenneth J.
    Goldman’s “Recursion Practice Problems”**
    Link: Washington University in St. Louis: Kenneth J. Goldman’s
    [“Recursion Practice
    Problems”](http://www.cs.wustl.edu/~kjg/cse131/modules/recursion/lab.html) (HTML)  
      
     Instructions: By clicking the on link above, you will access 10
    practice problems based on a small recursive program. Try to answer
    these questions before.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.


