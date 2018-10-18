# Whiteboarding

## Learning Competencies
- Develop best practices for whiteboarding during a technical interview
- Determine how to respond to questions that are unfamiliar

## Summary

Whiteboarding is a big part of technical interviews. Here are some resources for you to practice shared with us via our Whiteboarding mentor, Phil Corliss - Contact: pcorliss@gmail.com


### Array Intersection
In ruby there's an array intersection operator. Try implementing it yourself using a brute force method with a time complexity of O(n^2), a method that uses hashes in unexpected ways with complexity of O(n) and a sorting solution with complexity of O(nlogn).

2.1.1 :009 > a = [ 1, 3, -4, 5, 6]; b = [2, 3, 4, 6, 77]
 => [2, 3, 4, 6, 77]
2.1.1 :010 > a & b
 => [3, 6]

Check out this [site](http://www.sysexpand.com/?path=exercises/array-intersection) if you get stuck.

### group_by in Ruby Enumerable
In ruby there's a group_by method on Enumerable. Try implementing it yourself. Take some time to think on how to implement it. Don't worry if you can't recall the syntax for accepting blocks.

(1..6).group_by { |i| i%3 }
 => {0=>[3, 6], 1=>[1, 4], 2=>[2, 5]}

### Scaling Interview Questions
[Scalability Fundamentals](http://www.hiredintech.com/app#scalability-fundamentals)

### Great resources on Big-O Notation and interviewing
* [Hacking Coding Interview](http://www.restlessprogrammer.com/2013/09/hacking-coding-interview.html)
* [Bigocheatsheet.com](http://bigocheatsheet.com)
* [A Beginners Guide to Big O Notation](http://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/)
* [Five Essential Phone Screen Questions](https://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions)
* Cracking the Coding Interview [Book]

### Katas that you'll likely run into in an interview

* [Ruby Quiz Bowling Scores](http://rubyquiz.strd6.com/quizzes/181-bowling-scores)
* [Ruby Quix 11](http://rubyquiz.com/quiz11.html)
* [Ruby Quiz 22](http://rubyquiz.com/quiz22.html)
* [Ruby Quiz 154](http://rubyquiz.com/quiz154.html)

### Great Series of lectures from Berkely on Data Structures

* [Berkeley CS61B - Lecture](https://www.youtube.com/watch?v=QMV45tHCYNI&list=PL4BBB74C7D2A1049C)

### An example of adding binary numbers via a wooden mechanical machine

* [Wooden Binary Adding Machine](https://www.youtube.com/watch?v=4yBGbozevqs)
