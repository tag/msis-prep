---
authors:
    - Drake Lamp
date: 2020-10-03
---

## During the MSIS program

During your time in the MSIS program you will be required to model processes using <abbr title = "Business Process Model and Notation"> BPMN </abbr>. It is important that you understand general modeling techniques that may aid you throughout the program on various assignments and group projects. As a result, it is expected that students entering the MSIS program are able to fully utilize <abbr title = "Unified Modeling Language"> UML </abbr> when analyzing cases and creating Sequence Diagrams.

You are encouraged to practice with Microsoft Visio as this is primarily used throughout the program. However, below are a few other options which will be sufficient.

*  [Microsoft Visio][msvisio] - [Getting Started with MS Visio][msVisioGS]
[msvisio]: https://uits.iu.edu/iuanyware
[msVisioGS]:https://www.youtube.com/watch?v=b09dKHvu4-4

*  [Draw.io][drawio] - [Getting Started with Draw.io][drawGS]
[drawio]:https://app.diagrams.net/
[drawGS]:https://www.youtube.com/watch?v=Z0D96ZikMkc

*  [Lucidchart][lucidChart] - [Getting Started with Lucidchart][lucidGS]
[lucidChart]:https://LucidChart.com/
[lucidGS]:https://www.youtube.com/watch?v=QFVZVaOcz7E

## Major concepts

**You should be able to construct sequence diagrams** by utilizing the **key components** outlined below. The knowledge throughout this section will build upon that outlined within the _Use Case Diagram_ module.

1. Explain the three different _**classes**_ that make up a sequence diagram.
2. Understand the role _**actors**_ play within a sequence diagram (refer back to the _Use Case Diagram_ module!).
3. Know where a _**lifeline**_ is used.
4. Understand the basic flow of messages using _**execution occurrence**_.
5. Describe a _**kill**_, and understand when it is to be used within your diagrams.
6. Explain the different types of _**communication**_ methods within a sequence diagram.
7. Understand how to build _**loops**_ and be able to determine when they are best used within your final diagrams.


## Components Explained

**Disclaimer**: Some of these concepts may go by slightly different names throughout both the Resource and Practice sections. However, there uses remain the same.

1. Types of _**Classes**_
    1. Boundaries: Boundaries are _only_ able to talk to Controllers or Actors.
    2. Controllers: Implement the flow of logic for the sequence diagram; it is recommended that you only have _**one**_ controller per diagram.  
    3. Entities: Represents data within a system.
2. _**Actors**_: Those who interact with the system; actors are _only_ able to 'talk' to Boundaries.
3. _**Lifeline**_: Represented as dashed lines, these _must_ go from the top of the diagram to the bottom.
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

*  It will benefit you to start with the following article, [Sequence Diagrams 101 (General Overview)][visual-link][^citation-one]. serves as a good overview of sequence diagrams by discussing their purpose as well as diving more into _**actors, lifelines, activations, loops, etc.**_

[visual-link]:https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-sequence-diagram/

[^citation-one]: ["What Is Sequence Diagram?"](https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-sequence-diagram/) What Is Sequence Diagram?", Visual Paradigm.

*  Next, you may find it beneficial to read the following chapter. [Sequence Diagrams (Chapter 10, with Questions)][chapter-resource][^citation-two] This resource gives additional review of Sequence Diagrams, while placing an emphasis on _**messages.**_

[chapter-resource]:https://www.cpe.ku.ac.th/~plw/oop/e_book/ood_with_java_c++_and_uml/ch12.pdf
[^citation-two]: ["Sequence Diagram?"](https://www.cpe.ku.ac.th/~plw/oop/e_book/ood_with_java_c++_and_uml/ch12.pdf) Kasetsart University.

*  Ready for a step-by-step example? If so, refer to the following video. [Sequence Diagrams 101 (Video Refresher)][youtube-one][^citation-three] It also provides additional explanations of _**classes, actors, lifelines, messages.**_

[![Sequence Diagrams 101 (Video Refresher)](https://img.youtube.com/vi/_Mzi1rYtI5U/0.jpg)](https://www.youtube.com/watch?v=_Mzi1rYtI5U)
[youtube-one]:https://www.youtube.com/watch?v=_Mzi1rYtI5U

[^citation-three]: Master2Teach. [“Sequence Diagram - Step by Step Guide with Example.”](https://www.youtube.com/watch?v=_Mzi1rYtI5U) Online video clip. YouTube. YouTube, 14 April 2020. Web. 10 October 2020.

*  Interested in learning how Sequence Diagrams can improve a technical coding project? Watch the following video! [Sequence Diagrams (Coding Example)][youtube-two].[^citation-four] It not only brings the two together, but it also continues to cover _**messages.**_

[![Sequence Diagrams (Coding Example)](https://img.youtube.com/vi/EoXKS-0S3qs/0.jpg)](https://www.youtube.com/watch?v=EoXKS-0S3qs)
[youtube-two]:https://www.youtube.com/watch?v=EoXKS-0S3qs
[^citation-four]: Jones, Brandan. [“Model Method Calls with UML Sequence Diagram.”](https://www.youtube.com/watch?v=EoXKS-0S3qs) Online video clip. YouTube. YouTube, 23 June 2018. Web. 10 October 2020.

*  Bringing things together, it is recommended you watch the following video, [Sequence Diagrams (Tutorial/Practice)][youtube-three].[^citation-five] This video walks through constructing a Sequence Diagram by using LucidChart and further covers _**lifelines, messages, loops.**_

[![Sequence Diagrams (Tutorial/Practice)](https://img.youtube.com/vi/pCK6prSq8aw/0.jpg)](https://www.youtube.com/watch?v=pCK6prSq8aw)
[youtube-three]:https://www.youtube.com/watch?v=pCK6prSq8aw
[^citation-five]: Lucidchart. [“How to make a UML Sequence Diagram.”](https://www.youtube.com/watch?v=pCK6prSq8aw) Online video clip. YouTube. YouTube, 27 August 2018. Web. 10 October 2020.


*  Are you just looking for a quick refresher to Sequence Diagrams? We recommend checking out the following video, [Use Case Diagrams to Sequence Diagrams][youtube-four].[^citation-six] It covers both _**constructing a sequence diagram**_ while relating it back to Use Case Diagrams.

[![Converting Use Case Diagrams to Sequence Diagrams](https://img.youtube.com/vi/aaAjndV5kBg/0.jpg)](https://www.youtube.com/watch?v=aaAjndV5kBg)
[youtube-four]:https://www.youtube.com/watch?v=aaAjndV5kBg
[^citation-six]: VisualParadigm. [“How to Elaborate Use Case with UML Sequence Diagram.”](https://www.youtube.com/watch?v=aaAjndV5kBg) Online video clip. YouTube. YouTube, 2 October 2013. Web. 10 October 2020.

## Practice

Here is a small list of practice problems (with answers!) that you may find useful as you learn and/or refresh on Sequence Diagrams.

*  **ATM Withdrawal:** As a user, arrive to the ATM and conduct the standard withdrawal process in order to retrieve money. This set of practice problem(s) includes both a non-verifying and verifying sequence. [Answer Provided][atm-practice] [^citation-seven]
[atm-practice]:https://norsamsiah.files.wordpress.com/2010/01/lab4answer1.pdf

[^citation-seven]: Sani, Nor Samsiah. ["Lab 004 - In-Class Exercise Answer"](https://norsamsiah.files.wordpress.com/2010/01/lab4answer1.pdf)

*  **Name elements, Identify Errors, and efficiency issues:** The attached exercise(s) allow you to practice identifying elements of a Sequence Diagrams along with ensuring you are able to detect errors and efficiency problems. [Answers Provided][various-exercises] [^citation-eight]
[various-exercises]:http://users.csc.calpoly.edu/~jdalbey/305/Labs/SequenceDiagramExercises.html

[^citation-eight]: Dalbey, John. ["Sequence Diagram Exercises"](https://users.csc.calpoly.edu/~jdalbey/305/Labs/SequenceDiagramExercises.html), California Polytechnic State University.

*  **Interactions with Actor and System:** Assume the role of a Country Club owner, you will be required to make requests to the system in order to identify active members, club sales as well as what the those sales consisted of. Before moving onto the next request ensure that the Owner has received the previously requested information.[^citation-nine]
<details class="example">
<summary>Answer</summary>
![alt text](/images/club-practice.png)
</details>

[^citation-nine]: Exercise adapted from Professor Alex Lopes, Indiana University at Bloomington, BUS-S310 Class examples.
