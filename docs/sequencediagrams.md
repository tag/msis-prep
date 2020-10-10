---
authors:
    - Drake Lamp
date: 2020-10-03
---

## During the MSIS program

During your time in the MSIS program you will be required to model processes using _BPMN_, primarily in the _APA_ (Agile, Processes, and Automation) module. However, it is important that you understand general modeling techniques that may aid you throughout the program on various assignments and group projects. As a result, it is expected that students entering the MSIS program are able to fully utilize _**UML**_ (Unified Modeling Language) when analyzing cases and creating Sequence Diagrams.

You are encouraged to practice with Microsoft Visio as this is primarily used throughout the program. However, below are a few other options which will be sufficient.

[Microsoft Visio][msvisio] - [Getting Started with MS Visio][msVisioGS]
[msvisio]: https://uits.iu.edu/iuanyware
[msVisioGS]:https://www.youtube.com/watch?v=b09dKHvu4-4

[Draw.io][drawio] - [Getting Started with Draw.io][drawGS]
[drawio]:https://app.diagrams.net/
[drawGS]:https://www.youtube.com/watch?v=Z0D96ZikMkc

[Lucidchart][lucidChart] - [Getting Started with Lucidchart][lucidGS]
[lucidChart]:https://LucidChart.com/
[lucidGS]:https://www.youtube.com/watch?v=QFVZVaOcz7E

## Major concepts

**Please note**: Some of these concepts may go by slightly different names throughout both the Resource and Practice sections. However, their uses remain the same.

1. Types of _**Classes**_
    1. Boundaries: Boundaries are only able to talk to Controllers or Actors.
    2. Controllers: Implement the flow of logic for the sequence diagram; it is recommended that you only have _**one**_ controller per diagram.  
    3. Entities: Represents data within a system.
2. _**Actors**_: Those who interact with the system; actors are only able to 'talk' to Boundaries.
3. _**Lifeline**_: Represented as dashed lines, these must go from the top of the diagram to the bottom.
4. _**Execution Occurrence**_: Used to represent the time when a class is sending and/or receiving messages within the sequence diagram.
5. _**Kills**_: Rarely used, however, meant to kill any object that is no longer needed.
6. _**Communication**_ in sequence diagrams
    1. Message(X,Y): Used to pass parameters in a process.
    2. FoundMessage(X,Y): This is a message where the origin of a message is not shown within the current diagram.
    3. AsynchronousMessage(X,Y): Used when the message caller does not wait for a response before proceeding with other actions.
    4. Return Value: Indicates that a message receiver is done processing a message and returning control to the initial message caller.
7. _**Frames**_ in sequence diagrams
    1. Loop Frame: Often used to showcase repeated processes.
    2. Opt Frame: Used to showcase conditional statements much like the usual "If, Else" statement in programing.
    3. Alt Frame: Much like 'Opt' Frames, Alt Frames are used for conditional statements. However, Alt Frames can be thought of as "If, Else-if, and Else" statements.

## Resources

*  [Sequence Diagrams 101 (General Overview)][visual-link][^citation-one] This article serves as a good overview of sequence diagrams by discussing their purpose, main components, and how to use them.
[visual-link]:https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-sequence-diagram/
[^citation-one]: "What Is Sequence Diagram?", Visual Paradigm, www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-sequence-diagram/.  

*  [Sequence Diagrams (Chapter 10, with Questions)][chapter-resource][^citation-two] The attached Chapter offers a high-level overview of sequence diagrams alongside various exercises you may complete.
[chapter-resource]:https://www.cpe.ku.ac.th/~plw/oop/e_book/ood_with_java_c++_and_uml/ch12.pdf
[^citation-two]: "Sequence Diagrams", Kasetsart University, www.cpe.ku.ac.th/~plw/oop/e_book/ood_with_java_c++_and_uml/ch12.pdf

*  [Sequence Diagrams 101 (Video Refresher)][youtube-one][^citation-three] This video offers a very low-level explanation of sequence diagrams and its components while integrating a step-by-step example.
[![Sequence Diagrams 101 (Video Refresher)](https://img.youtube.com/vi/_Mzi1rYtI5U/0.jpg)](https://www.youtube.com/watch?v=_Mzi1rYtI5U)
[youtube-one]:https://www.youtube.com/watch?v=_Mzi1rYtI5U
[^citation-three]: Master2Teach. “Sequence Diagram - Step by Step Guide with Example.” Online video clip. YouTube. YouTube, 14 April 2020. Web. 10 October 2020.

*  [Sequence Diagrams (Coding Example)][youtube-two][^citation-four] The attached video compares sequence diagrams to coding examples in an effort to relate the two together.
[![Sequence Diagrams (Coding Example))](https://img.youtube.com/vi/EoXKS-0S3qs/0.jpg)](https://www.youtube.com/watch?v=EoXKS-0S3qs)
[youtube-two]:https://www.youtube.com/watch?v=EoXKS-0S3qs
[^citation-four]: Jones, Brandan. “Model Method Calls with UML Sequence Diagram.” Online video clip. YouTube. YouTube, 23 June 2018. Web. 10 October 2020.

*  [Sequence Diagrams (Tutorial/Practice)][youtube-three][^citation-five] This video explains what a sequence diagram is followed by a creating an example using Lucidchart.
[![Sequence Diagrams (Tutorial/Practice)](https://img.youtube.com/vi/pCK6prSq8aw/0.jpg)](https://www.youtube.com/watch?v=pCK6prSq8aw)
[youtube-three]:https://www.youtube.com/watch?v=pCK6prSq8aw
[^citation-five]: Lucidchart. “How to make a UML Sequence Diagram.” Online video clip. YouTube. YouTube, 27 August 2018. Web. 10 October 2020.

*  [Use Case Diagrams to Sequence Diagrams][youtube-four][^citation-six] This brief video offers a quick refresher into constructing a sequence diagram.
[![Converting Use Case Diagrams to Sequence Diagrams](https://img.youtube.com/vi/aaAjndV5kBg.jpg)](https://www.youtube.com/watch?v=aaAjndV5kBg)
[youtube-four]:https://www.youtube.com/watch?v=aaAjndV5kBg
[^citation-six]: VisualParadigm. “How to Elaborate Use Case with UML Sequence Diagram.” Online video clip. YouTube. YouTube, 2 October 2013. Web. 10 October 2020.

## Practice

Here is a small list of practice problems (with answers!) that you may find useful as you learn and/or refresh on Sequence Diagrams.

*  [ATM Withdrawal (Answer Provided)][atm-practice] As a user, arrive to the ATM and conduct the standard withdrawal process in order to retrieve money. This set of practice problem(s) includes both a non-verifying and verifying sequence.[^citation-seven]
[atm-practice]:https://norsamsiah.files.wordpress.com/2010/01/lab4answer1.pdf

[^citation-seven]: Sani, Nor Samsiah. "Lab 004 - In-Class Exercise Answer". norsamsiah.files.wordpress.com/2010/01/lab4answer1.pdf.

*  [Name elements, Identify Errors, and efficiency issues][various-exercises] The attached exercise(s) allow you to practice identifying elements of a Sequence Diagrams along with ensuring you are able to detect errors and efficiency problems.[^citation-eight]
[various-exercises]:http://users.csc.calpoly.edu/~jdalbey/305/Labs/SequenceDiagramExercises.html

[^citation-eight]: Dalbey, John. "Sequence Diagram Exercises", users.csc.calpoly.edu/~jdalbey/305/Labs/SequenceDiagramExercises.html.

*  [Interactions with Actor and System (Answer Provided)][club-practice] Assume the role of a Country Club owner, you will be required to make requests to the system in order to identify active members, club sales as well as what the those sales consisted of. Before moving onto the next request ensure that the Owner has received the previously requested information.[^citation-nine]
[club-practice]:/images/club-practice.png

[^citation-nine]: Exercise adapted from Professor Alex Lopes, Indiana University at Bloomington, BUS-S310 Class examples.

*  _**More Coming Soon!**_
