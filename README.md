## iPrep Week 2: Big O and Hashtables

* **Big O Notation**: Describing an algorithm's complexity
* **Hashtables**: Stores data with key value pairs

What you will submit:
- A GitHub repo with this README file (with the boxes checked).
- Create a GIF showing your Interviewbit dashboard (see below) showing exercises you've done.

### Required tasks

**Big O Notation**

- [x] Watch [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)(8m)
  - I have learned that...
    4 rule to determine big O ( complex of algorithm )

    * Different step get added
    * Drop constants
      < O(2n) => O(n)
    * Different input -> different variables
      - different array has different size
    * Drop non-determine term < O(n+n2) => O(n2) >
- [x] Read [Big O Notation in plain English](http://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation) and write down what you learned from it
  - I have learned that...
    define : Big-O notation is a relative representation of the complexity of an algorithm
        O(1): known as Constant complexity
        O(n) or linear complexity
        O(n2) or quadratic complexity
        O(log n): known as Logarithmic complexity
- [x] Visit http://bigocheatsheet.com/ and think about how useful it could be to you
  - This sheet makes more sense to me now 
- [x] Watch LogN in 5m: https://www.youtube.com/watch?v=kjDR1NBB9MU
  - I have learned that...
    binary-search has O:(log N)
        rule : n * (1/2)^x  = 1 
        step = Log2(n)
    apply to sort : => quicksort 
    quick sort :
    sperate array : move lesser to lelf side) + greater to right side_(:compare with piviot)
    stop when has 1 element each array 
    piviot is position sperate
    quicksort O(nlogN)

  
**Hashtables**

- [x] Read [InterviewCake Hashtable](https://www.interviewcake.com/concept/java/hash-map?)
- [x] Watch concept video: [HackerRank Video: Hash Tables](https://www.youtube.com/watch?v=shs0KM3wKv8) (6m)

Extras: 
- [ ] [Introducing Hash Tables](https://www.youtube.com/watch?v=MfhjkfocRR0) (7m)
- [ ] [Hash Table Algorithms](https://www.youtube.com/watch?v=Ke_tII6Y0GE) (7m)

**Coding**

- [x] Set up an account on Interviewbit.com and start the [Programming course](https://www.interviewbit.com/courses/programming/)
- [ ] Finish at least 2 tasks on Exercism

### Optional tasks

Some tasks are the same as optional tasks in Assignment 1.

- [ ] Do more tasks on exercism
- [ ] Finish [Time Complexity chapter](https://www.interviewbit.com/courses/programming/topics/time-complexity) in Level 1 of Interviewbit
- [ ] Finish [Arrays chapter]((https://www.interviewbit.com/courses/programming/topics/arrays/)) in Level 2 of Interviewbit
- [ ] Finish [Math chapter](https://www.interviewbit.com/courses/programming/topics/math/) in Level 2 of Interviewbit.
