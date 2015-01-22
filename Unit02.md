**Unit 2: Sets, Part I** <span id="2"></span> 
*In this unit, you will explore the ideas of what is called ‘naive set
theory.’  Contrasted with ‘axiomatic set theory,’ naive set theory
assumes that you already have an intuitive understanding of what it
means to be a set.  You should mainly be concerned with how two or more
given sets can be combined to build other sets and how the number of
members (i.e. the cardinality) of such sets is related to the
cardinality of the given sets.*

**Unit 2 Time Advisory**  
This unit should take approximately 10.75 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Introduction: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.1: 1.75 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.2: 3.25 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.3: 1.5 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 3.4: 1.25 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Formally define a set using set builder notation.
-   Identify and explain the difference between being a member of a set
    and being a subset of a set.
-   Build new sets from existing ones using the set operations,
    including unions, intersections, complements, symmetric difference,
    Cartesian product, and relative complements.
-   Verify properties of sets (e.g., distributive laws, DeMorgan’s laws,
    etc.)
-   Compute the power set of a given set.
-   Compute the cardinality of the union (intersection) of two finite
    sets given the cardinalities of the sets and their intersection
    (union).
-   Determine if two sets are *equivalent*.

-   **Lecture: YouTube: Indian Institute of Technology Madras’ National
    Programme on Technology Enhanced Learning (NPTEL): Dr. Kamala
    Krithivasan’s “Lecture 10: Sets”**
    Link: YouTube: Indian Institute of Technology Madras’ National
    Programme on Technology Enhanced Learning (NPTEL): Dr. Kamala
    Krithivasan’s [“Lecture 10:
    Sets”](http://www.youtube.com/watch?v=9AUCdsmBGmA) (YouTube)  
      
     Instructions: Please click on the link above and watch this
    lecture.  This lecture defines sets and will familiarize you with
    set notation and set language.  
      
     Watching this lecture and pausing to take notes should take
    approximately 1 hour and 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use on the
    webpage displayed above.

-   **Reading: Old Dominion University: Shunichi Toida’s “Introduction
    to Set Theory”, (HTML) “Representation of Sets”, (HMTL) “Basics of
    Sets”, (HTML and Java) and “Mathematical Reasoning”**

    Links: Old Dominion University: Shunichi Toida’s [“Introduction to
    Set
    Theory”](http://www.cs.odu.edu/~toida/nerzic/content/set/intr_to_set.html),
    (HTML) [“Representation of
    Sets”](http://www.cs.odu.edu/~toida/nerzic/content/set/representation.html),
    (HMTL) [“Basics of
    Sets”](http://www.cs.odu.edu/~toida/nerzic/content/set/basics.html),
    (HTML and Java) and [“Mathematical
    Reasoning”](http://www.cs.odu.edu/~toida/nerzic/content/set/math_reasoning.html)
    (HTML)  
      
     Instructions: Please click on the links above and read these
    webpages in their entirety.  These texts discuss the basics of set
    theory.  Note that there are three ways to define a set.  The third
    method, recursion, will come up again later in the course, but this
    is a great time to learn it.  
      
     Reading these webpages should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.1 What Is a Set? Set Builder Notation** <span id="2.1"></span> 
**2.1.1 The Empty Set, the Universal Set** <span id="2.1.1"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson's Discrete Mathematics: “Arithmetic, Logic and Numbers,
    Unit SF: Sets and Functions”**

    Link: University of California, San Diego: Edward Bender and S.
    Williamson's *Discrete Mathematics*: [“Arithmetic, Logic and
    Numbers, Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf)
    (PDF)  
      
     Instructions: Please click on the link above to download the PDF. 
    Please read pages SF-1 through SF-8 of the file for an introduction
    to sets, set notation, set properties and proofs, and ordering
    sets.  
      
     Reading this article should take approximately 1 hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson.  Please note
    that this material is under copyright and cannot be reproduced in
    any capacity without explicit permission from the copyright holder.

-   **Web Media: YouTube: Kasidej Anchaleenukoon’s “Set Theory”**
    Link: YouTube: Kasidej Anchaleenukoon’s [“Set
    Theory”](http://www.youtube.com/watch?v=F-srGbGD_C8&feature=related)
    (YouTube)  
      
     Instructions: Please click the link above and watch this video for
    an elementary introduction to set theory.  This will be useful to
    you in case you feel uneasy about the reading above.  
      
     Watching this video and pausing to take notes should take
    approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use on the
    webpage displayed above.

**2.1.2 The Characteristic Function of a Set (Also Called the Indicator
Function)** <span id="2.1.2"></span> 
*Note: This topic is covered by the Bernstein reading assigned below
sub-subunit 2.1.1.  In particular, make sure to focus on “Definition 2:
Characteristic Function,” starting on page 10 of the PDF.*

**2.1.3 Sets with Sets as Members** <span id="2.1.3"></span> 
-   **Reading: University of California, San Diego: Edward Bender and S.
    Williamson’s Discrete Mathematics: “Arithmetic, Logic and Numbers,
    Unit SF: Sets and Functions”**

    Link: University of California, San Diego: Edward Bender and S.
    Williamson’s *Discrete Mathematics*: [“Arithmetic, Logic and
    Numbers, Unit SF: Sets and
    Functions”](http://www.saylor.org/site/wp-content/uploads/2011/09/CS202-Sets-and-Functions-Edward-Benderand-S.-Gill-Williamson.pdf)
    (PDF)  
      
     Instructions: Please click on the link above to download the PDF. 
    Please read pages SF-9 through SF-11 to learn about subsets of
    sets.  This text also is useful for learning how to prove various
    properties of sets.  If needed, review pages SF1-SF8, which were
    covered in sub-subunit 2.1.1 above.  In particular, please focus on
    example 9.  
      
     Reading these sections should take approximately 30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Edward Bender and S. Williamson.  Please note
    that this material is under copyright and cannot be reproduced in
    any capacity without explicit permission from the copyright holder.

**2.2 Building New Sets from Given Sets** <span id="2.2"></span> 
-   **Reading: Old Dominion University: Shunichi Toida’s “Set
    Operations”**
    Link: Old Dominion University: Shunichi Toida’s [“Set
    Operations”](http://www.cs.odu.edu/~toida/nerzic/content/set/set_operations.html)
    (HTML and Java)  
      
     Instructions: Please click on the link above and read the entire
    webpage.  Then test your understanding by working the four problems
    at the bottom.  
      
     Reading this webpage and completing these problems should take
    approximately 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use on the
    webpage displayed above.

**2.2.1 Properties of Union, Intersection, and Complementation** <span
id="2.2.1"></span> 
-   **Reading: Old Dominion University: Shunichi Toida’s “Properties of
    Set Operation”**
    Link: Old Dominion University: Shunichi Toida’s [“Properties of Set
    Operation”](http://www.cs.odu.edu/~toida/nerzic/content/set/set_op_prop.html)
    (HMTL)  
      
     Instructions: Please click on the link above and read the entire
    webpage.  It is important that you become aware that sets combine
    under union and intersection in very much the same ways that numbers
    combine under addition and multiplication.  For example, AUB=BUA is
    a way to say *union* is commutative in the same way as x + y = y + x
    says addition is commutative.  One difference, however, is that the
    properties of addition and multiplication are defined as part of the
    number system (in our development) whereas the properties of sets
    under the operations we have defined are provable and hence must be
    proved.  
      
     Reading this webpage should take approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use on the
    webpage displayed above.

-   **Reading: Simpson College’s Department of Computer Science: Lydia
    Sinapova’s “Boolean Algebra”**
    Link: Simpson College’s Department of Computer Science: Lydia
    Sinapova’s [“Boolean
    Algebra”](http://faculty.simpson.edu/lydia.sinapova/www/cmsc180/cmsc180-12/Sch175-12A.htm)
    (PDF)  
      
     Instructions: Please click on the link above, scroll down the
    webpage to week 7, and click on the link for “Boolean Algebra” to
    download the lecture as a PDF.  Please read this entire lecture,
    paying special attention to the definition of Boolean Algebra and to
    the isomorphism between the two systems of propositional logic and
    that of sets.  Work the three exercises at the bottom of the PDF and
    then have a look at the solutions at the end of the document.  Note
    that this reading also covers the topic outlined in sub-subunit
    2.2.2.  
      
     Reading this lecture and completing these exercises should take
    approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use on the
    webpage displayed above.

**2.2.2 The (Boolean) Algebra of Subsets of a Set** <span
id="2.2.2"></span> 
-   **Reading: The University of Western Australia: Greg Gamble’s “Set
    Theory, Logic, and Boolean Algebra”**

    Link: The University of Western Australia: Greg Gamble’s [“Set
    Theory, Logic, and Boolean
    Algebra”](http://school.maths.uwa.edu.au/~gregg/Academy/2011/)
    (PDF)  
      
     Instructions: Please click on the first link above and then select
    the link to the lecture “Set Theory, Logic, and Boolean Algebra” to
    download the PDF.  Please read the entire lecture.  
      
     Reading this lecture should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use on the
    webpage displayed above.

**2.2.3 Using Characteristic Functions to Prove Properties of Sets**
<span id="2.2.3"></span> 
-   **Reading: Jerusalem College of Technology: Dr. Th. Dana-Picard’s
    “The Characteristic Function of a Set”**

    Link: Jerusalem College of Technology: Dr. Th. Dana-Picard’s [“The
    Characteristic Function of a
    Set”](http://ndp.jct.ac.il/tutorials/Discrete/node42.html) (HTML)  
      
     Instructions: Please click on the link above and read the entire
    webpage.  This brief text will show you how to use characteristic
    functions to prove properties of sets.  However, there are other
    reasons to learn how to do this.  You will see later in the course
    that functions (not just characteristic functions play a critical
    role in the theory of cardinality (set size).  
      
     Reading this webpage should take approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3 The Cartesian Product of Two or More Sets** <span
id="2.3"></span> 
-   **Reading: Jerusalem College of Technology: Dr. Th. Dana-Picard’s
    “The Cartesian Product of Sets”**

    Link: Jerusalem College of Technology: Dr. Th. Dana-Picard’s [“The
    Cartesian Product of
    Sets”](http://ndp.jct.ac.il/tutorials/Discrete/node28.html) (HTML)  
      
     Instructions: Please click on the link above and read this webpage
    for a definition and overview of the Cartesian product of sets.  
      
     Reading this webpage should take approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.1 The Disjoint Union and Addition** <span id="2.3.1"></span> 
-   **Web Media: YouTube: American Public University’s “Disjoint Sets”**
    Link: YouTube: American Public University’s [“Disjoint
    Sets”](http://www.youtube.com/watch?v=lT2lw-XZLG0&feature=relmfu)
    (YouTube)  
      
     Instructions: Please click on the link above and watch this brief
    lecture on disjoint sets.  
      
     Watching this and pausing to take notes should take less than 15
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.2 The Cartesian Product and Multiplication** <span
id="2.3.2"></span> 
-   **Reading: Nikos Drakos and Ross Moore’s Discrete Mathematics: “The
    Cartesian Product of Sets”**

    Link: Nikos Drakos and Ross Moore’s *Discrete Mathematics*: [“The
    Cartesian Product of
    Sets”](http://ndp.jct.ac.il/tutorials/Discrete/node28.html) (HTML)  
      
     Instructions: Please click on the link above and read this webpage,
    paying special attention to the proof of proposition 3.3.3 at the
    end of the page.  There is a nice proof of this using characteristic
    functions, which you will be asked to produce later in the course.  
      
     Reading this webpage should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4 Counting Finite Sets** <span id="2.4"></span> 
**2.4.1 The Cardinality of the Power Set of a Set** <span
id="2.4.1"></span> 
-   **Web Media: YouTube: American Public University’s “Equivalent
    Sets”**
    Link: YouTube: American Public University’s [“Equivalent
    Sets”](http://www.youtube.com/watch?v=y8sLJqXhpkE&feature=relmfu)
    (YouTube)  
        
     Instructions: Please click on the link above and watch this
    lecture, which discusses equivalent sets.  
        
     Watching this lecture and pausing to take notes should 15
    minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4.2 The formula |A| + |B| = |A U B| + |A U B|** <span
id="2.4.2"></span> 
-   **Reading: University of Hawaii: G.N. Hile’s “Set Cardinality”**
    Link: University of Hawaii: G.N. Hile’s [“Set
    Cardinality”](http://www.math.hawaii.edu/~hile/math100/setsd.htm)
    (HTML)  
      
     Instructions: Please click on the link above and read this webpage,
    which demonstrates the basic inclusion/exclusion equation outlined
    in the title of this subunit.  The examples on this webpage are
    especially interesting; pay attention to example 2, which is about
    playing cards.  
      
     Reading this webpage and taking notes should take approximately 1
    hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation’s “Elementary Set Theory
    Homework Set”**
    Link: The Saylor Foundation’s [“Elementary Set Theory Homework
    Set”](http://www.saylor.org/site/wp-content/uploads/2012/11/MA111-Assessment-2-Elementary-Set-Theory-Homework-Set-FINAL.pdf)
    (PDF)  
      
     Instructions: Please click on the link above, and complete the
    following problems, showing all work.  These problems cover the
    topics of elementary set theory.  When you are done, check your work
    against the answers provided in the accompanying solutions file, the
    Saylor Foundation’s [“Elementary Set Theory Homework Set
    Solutions”](http://www.saylor.org/site/wp-content/uploads/2012/11/MA111-Assessment-2-Elementary-Set-Theory-Homework-Set-Solutions-FINAL.pdf)
    (PDF).  
      
     This exercise set should take between 2 and 3 hours to complete,
    depending on your comfort level with the material.


