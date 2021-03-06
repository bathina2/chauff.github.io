---
layout: page
title: Teaching
---

## MSc thesis supervision

I am supervising students who conduct research in *information retrieval* and *natural language processing*. For both research directions, taking a look at papers at recent conferences (such as SIGIR, CIKM, WSDM, EMNLP, ACL) and ongoing benchmark efforts (MSMarco, SQUAD 2.0, GLUE, decaNLP, TREC) will help to figure out a topic of interest.

I also have a set of topics that I am ready to give away:
- Evaluate the usability of [Macaw](https://arxiv.org/pdf/1912.08904.pdf), a recently inroduced Conversational Information Seeking Platform, possibly extend it and run an interactive IR study with it.
- Extend [SearchX](https://github.com/felipemoraes/searchx), a collaborative search engine we built in-house, with shared workspace capabilities and run an interactive IR study with it.
- Analyze the effectiveness of multi-task learning for different IR tasks.
- Evaluate the use of efficient context-sensitive embedding approaches (variations of BERT & Co that do not rely on hundreds of millions of parameters) for different IR tasks and under performance constraints.
- Design, build and evaluate an extension to Visual Studio Code that enables information seeking for programming tasks directly in the IDE.
- Investigate UI elements that make collaborative search in the mobile setting (where screen space is a premium) a real possibility.

## Courses
 
 Below are the resources I have developed for my courses (some are more up-to-date than others): 
 *Big Data Processing*, *Web and Database Technology* and *Information Retrieval*.

### Big Data Processing

Since 2013/2014 I have been teaching the second year Bachelor course *Big Data Processing* at TU Delft (with 2016/17 being the last time for now). The course covers a range of technologies in the Hadoop ecosystem after a short excursion into the streaming world; 
I created the material based on a number of great books, including [Mining of Massive Datasets](http://www.mmds.org/),
[Data-Intensive Text Processing with MapReduce](https://lintool.github.io/MapReduceAlgorithms/), 
[Hadoop: The Definite Guide](http://shop.oreilly.com/product/0636920033448.do), [Programming Pig](http://chimera.labs.oreilly.com/books/1234000001811/index.html)
and [ZooKeeper](http://shop.oreilly.com/product/0636920028901.do). 

#### Slides - 2016/17 Edition
- [Introduction](../documents/bdp/intro.pdf)
- [Streams I](../documents/bdp/streaming1.pdf)
- [Streams II](../documents/bdp/streaming2.pdf)
- [MapReduce](../documents/bdp/mapreduce.pdf)
- [HDFS/GFS](../documents/bdp/gfs.pdf)
- [Scheduling](../documents/bdp/hadoop-ctd.pdf)
- [Algorithm design for MapReduce](../documents/bdp/design_patterns_db.pdf)
- [Pig I](../documents/bdp/pig_intro.pdf)
- [Pig II](../documents/bdp/pig_advanced.pdf)
- [Graph algorithms](../documents/bdp/graph.pdf)
- [Giraph](../documents/bdp/graph_giraph.pdf)
- [ZooKeeper](../documents/bdp/coordination_zookeeper.pdf)
- 2 more lecture on Spark completed this course.

#### Assignments - 2016/17 edition
- [Assignment 1: Streaming](../documents/bdp/assignment1.pdf)
- [Assignment 2: Streaming and Hadoop](../documents/bdp/assignment2.pdf)
- [Assignment 3: Hadoop](../documents/bdp/assignment3.pdf)
- [Assignment 4: Pig](../documents/bdp/assignment4.pdf) [data](../documents/bdp/data-assignment4.zip)
- [Assignment 5: Pig](../documents/bdp/assignment5.pdf) [data](../documents/bdp/data-assignment5.zip)
- [Assignment 6: Giraph](../documents/bdp/assignment6.pdf)
- [Assignment 7: Spark](../documents/bdp/assignment7.pdf)

#### A Sample of Previous Exams
- [Resit 2013/14](../documents/bdp/exam-1.pdf)
- [Final 2014/15](../documents/bdp/exam-2.pdf)
- [Resit 2014/15](../documents/bdp/exam-3.pdf)
- [Final 2015/16](../documents/bdp/exam-4.pdf)
- [Final 2016/17](../documents/bdp/exam-5.pdf)
 
#### Interactive quizzes
- [24 questions on streaming](http://chauff.github.io/documents/bdp-quiz/streaming.html)
- [32 questions on MapReduce/Hadoop](http://chauff.github.io/documents/bdp-quiz/hadoop.html)
- [10 questions on graphs and Giraph](http://chauff.github.io/documents/bdp-quiz/graph.html)
- [12 questions on Pig/Pig Latin](http://chauff.github.io/documents/bdp-quiz/pig.html)


### Web (and Database) Technology

Since 2013/2014 I have also been teaching the first year Bachelor course *Web and Database Technology* (known as TI1506 or CSE1500) at TU Delft, together with
[Alessandro Bozzon](http://alessandrobozzon.com/). I teach the Web technology part, which turned out to be quite a challenge due to
the wide variety of skill sets our incoming students possess (some work as Web developers, others have never written a single line of HTML
before the start of this course). 

In the 2018/19 edition, we had roughly 900 students taking the course and so I finally bit the bullet and started making extensive lecture transcripts (with self-check questions, demo code, assignments, etc.), split the materials into GitHub repos and created a good looking website: [https://chauff.github.io/Web-Teaching/](https://chauff.github.io/Web-Teaching/).

Feel free to use the materials with acknowledgement.

Needless to say that this is ongoing work at all times - web tech changes quickly.

### Information Retrieval

In 2019/20 I co-taught the MSc Information Retrieval course with Nava Tintarev, splitting it along an IR and NLP line. The course setup, slides and group projects can be found [here](https://github.com/chauff/IN4325).
