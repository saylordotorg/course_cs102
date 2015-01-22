**Unit 3: C++ Standard Template Library** <span id="3"></span> 
*Nearly every C++ programmer uses the C++ Standard Template Library
(STL), a powerful and highly useful library of generic-typed data
structures and algorithms. In this unit, we will learn how and why the
STL was originally developed. The unit will also introduce you to the
history and basics of templates and generic programming before
presenting the structures (Containers, Iterators, and Functors) and
algorithms that the Standard Template Library contains. By the end of
this unit, you will be familiar with the STL, its uses, and its
structures and algorithms.*

**Unit 3 Time Advisory**  
This unit should take you 18.5 hours to complete.  
  
 ☐    Subunit 3.1: 5 hours  
  
 ☐    Subunit 3.2: 6 hours  
  
 ☐    Subunit 3.3: 7 hours  
  
 ☐    Assessment: 0.5 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Demonstrate an understanding of the history of Generic Programming
    and the motivation behind the Generic Programming development;
-   Demonstrate an understanding of the detailed components used in
    Generic Programming; and
-   Demonstrate an understanding of the basic components used in the
    Standard Template Library with C++.

**3.1 History and Motivation** <span id="3.1"></span> 
-   **Reading: Wikibooks: “Ada Programming/Generics”**
    Link: Wikibooks: [“Ada
    Programming/Generics”](http://www.saylor.org/site/wp-content/uploads/2011/04/Ada-Programming_Generics.pdf)
    (PDF)  
        
     Instructions: Read this section in Wikibooks for an explanation of
    the history and purpose of generic programming and the precursor
    language, Ada. These chapters cover all of Subunit 3.1, including
    Section 3.1.1 and Section 3.1.2.   
      
     Note: Adais an Object-Oriented programming language used
    predominantly in military applications. It shares many of its
    features - including its structure and typing, with C++. While both
    languages were developed in the same year, Ada’s rapid adoption by
    certain circles within the Computer Science world led computer
    scientists to modify C++ by adopting some of Ada’s features in
    subsequent C++ releases. These changes are seen as an important
    evolutionary step in Object-Oriented programming. These materials
    cover generic programming, precursor Ada, and ANSI/ISO.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/).  You can find
    the original Wikibooks version of this article
    [here](http://en.wikibooks.org/wiki/Ada_Programming/Generics).

-   **Reading: InformIT: Andrew Binstock’s “An Interview with Alexander
    Stepanov and Paul McJones on Elements of Programming”**
    Link: InformIT: Andrew Binstock’s [“An Interview with Alexander
    Stepanov and Paul McJones on Elements of
    Programming”](http://www.informit.com/articles/article.aspx?p=1383185) (HTML)  
      
     Instructions: Read this article for a detailed interview with
    Alexander Stepanov and Paul McJones. They are largely responsible
    for the Standard Template Library and several methods of Generic
    programming.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2 Main Design Ideas** <span id="3.2"></span> 
-   **Reading: Dartmouth College: Afra Zomorodian’s “Computer
    Architecture”**
    Link: Dartmouth College: Afra Zomorodian’s [“Computer
    Architecture”](http://www.cs.dartmouth.edu/~afra/courses/4/x10/notes/23.php)
    (HTML)  
      
     Instructions: Read the following lecture in its entirety for a
    detailed explanation of how computer structure affects programming
    techniques and approaches. This lecture provides a detailed
    understanding of the affects that modern computer organization has
    on programming. This reading covers the following topics: ALU, von
    Neumann computation model, memory control, and organization.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3 Elements of C++ STL** <span id="3.3"></span> 
-   **Reading: University of Helsinki: Juha Karkkainen’s “Standard
    Template Library, STL”**
    Link: University of Helsinki: Juha Karkkainen’s [“Standard Template
    Library,
    STL”](http://www.cs.helsinki.fi/u/tpkarkka/alglib/k06/lectures/stl_intro.html)
    (HTML)  
      
     Instructions: Read this outline for an introduction to the
    importance of the standard template library and the elements that
    make up STL.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3.1 Containers** <span id="3.3.1"></span> 
-   **Reading: University of Helsinki: Juha Karkkainen’s “STL
    Containers”**
    Link: University of Helsinki: Juha Karkkainen’s [“STL
    Containers”](http://www.cs.helsinki.fi/u/tpkarkka/alglib/k06/lectures/containers.html)
    (HTML)  
      
     Instructions: Read this text for an understanding of the
    fundamental aspects of Containers in STL.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3.2 Iterators** <span id="3.3.2"></span> 
-   **Reading: Algorithmic Solutions’ “Introduction to Iterators”**
    Link: Algorithmic Solutions’ [“Introduction to
    Iterators”](http://www.algorithmic-solutions.info/leda_manual/introduction.html)
    (HTML)  
      
     Instructions: Read this webpage for an understanding of the
    fundamental aspects of Iterators in STL.  
      
     Terms of Use: Please respect the copyright and terms of use.<span
    id="cke_bm_549E" style="display: none;"> </span><span
    id="cke_bm_548E" style="display: none;"> </span><span
    id="cke_bm_547E" style="display: none;"> </span><span
    id="cke_bm_546E" style="display: none;"> </span>

**3.3.3 Complexity and Cost** <span id="3.3.3"></span> 
-   **Lecture: Massachusetts Institute of Technology: Eric Grimson and
    John Guttag’s “Complexity”**
    Link: Massachusetts Institute of Technology: Eric Grimson and John
    Guttag’s [“Complexity”](http://www.youtube.com/watch?v=Mxf5co9dHrw)
    (YouTube)  
      
     Also available in:  
     [Adobe Flash, PDF Transcript, MP4
    Download](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/video-lectures/lecture-8/)  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.2394447485.02394447490.2370889957?i=1857292917)  
      
     Instructions: Watch this 50-minute video for an understanding of
    the fundamental aspects of complexity and cost in programming.  
      
     Terms of Use: Eric Grimson and John Guttag, Introduction to
    Computer Science and Programming, Fall 2008. (Massachusetts
    Institute of Technology: MIT OpenCourseWare), http://ocw.mit.edu
    (Accessed September 21, 2011).  License: [Creative Commons BY-NC-SA
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/).  The
    original version can be found
    [here](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/video-lectures/lecture-8).

**3.3.4 Functors** <span id="3.3.4"></span> 
-   **Reading: University of Helsinki: Juha Karkkainen’s “STL
    Functors”**
    Link: University of Helsinki: Juha Karkkainen’s [“STL
    Functors”](http://www.cs.helsinki.fi/u/tpkarkka/alglib/k06/lectures/functors.html)
    (HTML)  
      
     Instructions: Read this section for an understanding of the
    fundamental aspects of Functors in STL.  This reading covers
    operator and predicates.  
      
     Terms of Use: Please respect the copyright and terms of use.

**Unit 3 Assessment** <span id="3.3.5"></span> 
-   **Assessment: Tech Interviews’ “Advanced C++ and STL Interview
    Questions”**
    Link: Tech Interviews’ [“Advanced C++ and STL Interview
    Questions”](http://www.techinterviews.com/advanced-c-and-stl-interview-questions)
    (HTML)  
      
     Instructions: By clicking the on link above, you will access a
    couple interview questions for C++ and STL.  Try to think about the
    answers to these questions before you read the answers.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


