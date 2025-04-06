[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course

# Week 2 
## Documentation Form Ashley 
Saw a video discussing the importance of code commenting and documentation in programming, emphasizing their various forms and best practices. It outlines three main categories of comments: code commenting, standardized documentation comments, and project documentation. 

The first category, code commenting, utilizes standard syntax within programming languages to provide context or explain specific code sections. The second type consists of comments designed for auto-generated documentation, typically used across frameworks and libraries to inform developers about the functionality of different methods or classes. Finally, project documentation, often found in README files, serves as a narrative introduction to a project, explaining its goals, usage, and contributing guidelines.

## Highlights From the Video 
-  Code comments provide clarity and context for specific sections of code, enhancing future readability.
-  Standardized documentation comments are auto-generated, offering consistent formatting and comprehensive details about methods and classes.
-  Project documentation in README files serves as a narrative introduction to projects, outlining their purpose and contributing guidelines.
-  Effective commenting is crucial but should be balanced with readable code to avoid clutter and obsolescence.
-  Developers are encouraged to prioritize documentation over commenting for improved knowledge sharing and comprehension.
-  Clear documentation supports onboarding and enhances community engagement in open-source projects.
-  Good documentation reflects a developer’s learning process, comprehension, and preparedness for career opportunities.
  
## Key Insights

  ### Commenting as Contextual Reference:
  Code comments are essential for providing clarity. They explain “why” certain approaches were taken, which is invaluable for future developers. Properly placed comments can make code chunks understandable, guiding developers on the rationale behind specific implementations.

 ### Standardized Documentation Benefits: 
 Documentation comments auto-generated through frameworks create a normalized structure for understanding APIs or libraries. These comments ensure that critical information about functions or methods is readily accessible, promoting uniformity across projects and helping users quickly identify capabilities.

 ### Project Documentation for Onboarding: 
 A well-crafted README file is crucial for effective onboarding. It outlines what the project does, how to use it, and contributes to fostering a welcoming environment for new contributors or users, thereby enhancing community engagement and collaboration.

 ### Balancing Comments and Code Readability: 
 While comments can help explain complex logic, over-commenting can lead to clutter and can create maintenance challenges as code evolves. Developers are encouraged to focus on writing clean, self-explanatory code with minimal reliance on comments.

###  Documentation as a Learning Reflection: 
  Prioritizing documentation over excessive commenting not only aids comprehension but also showcases a developer’s skills and understanding of their work. This practice can be particularly beneficial when seeking job opportunities, as it demonstrates growth and knowledge.

 ### Maintenance Considerations:
  Maintaining accurate comments can be tedious, and outdated comments can mislead users of the code. Hence, project documentation is recommended to take precedence for long-term usability and relevance, ensuring that the core purpose and structure of the project remain clear.

 ### Enhancing User Experience:
  Comprehensive documentation improves the user experience by allowing anyone to understand the project without having to decipher the code itself. This fosters a collaborative culture and empowers users to contribute effectively, aligning with modern development practices.






  # Week 3 
  ## Refactoring From Ashley 
Refactoring, originally popularized by Martin Fowler, is defined as a disciplined technique for restructuring existing code without altering its external behavior. The aim is to improve the internal structure of the code, making it more readable and maintainable without introducing bugs. The process involves small, incremental changes that cumulatively refine the codebase.

The lecture introduces important concepts such as “code smell,” which refers to indicators of potential issues in the code that may require attention. The speaker elaborates on various coding issues deemed as code smells, including code duplication, long methods, and excessive parameters in function signatures. Practical examples illustrate these points, showing how refactoring allows programmers to enhance code quality by modularizing complex functions, thus reducing duplication and increasing clarity.

## Highlight From the Video

###  Refactoring is Necessary  
Refactoring is essential to maintain and improve code quality without changing its external behavior. It ensures that the codebase remains clean, organized, and scalable over time.

### Code Smell Indicators  
Code smells alert developers to potential problems, prompting necessary refactoring. Common smells include long methods, duplicated code, and large classes, which can affect readability and maintainability.

### Incremental Changes  
Small, consistent refactoring efforts can lead to substantial improvements in the codebase. Avoid large, risky refactors — focus on bite-sized, manageable updates.

### Avoiding Technical Debt  
Regular refactoring helps prevent technical debt, which arises from temporary fixes or outdated code that can hinder future development.

### Modularization  
Breaking down long methods into smaller, focused functions enhances code readability, reusability, and testability. Follow the Single Responsibility Principle wherever possible.

### Opportunistic Refactoring  
Developers are encouraged to refactor code opportunistically as they work on new features or bug fixes. This keeps the codebase clean and healthy without requiring dedicated refactoring sprints.

### Establish Regular Refactoring Practices  
Incorporating refactoring into routine development practices and code reviews can greatly enhance long-term code management and team productivity.

 **Tip:** Make refactoring part of your daily workflow. Use code linters, unit tests, and commit messages to track and communicate your improvements.
 ---

## Key Insights

### Understanding Refactoring: 
Refactoring is a nuanced discipline that requires developers to carefully consider the internal structure of their code, focusing on readability and maintainability. The process should not disrupt the software’s external functionality, emphasizing the need for a methodical approach to changes.

### Weighing Cost vs. Benefit: 
Developers must balance the immediate benefits of refactoring against the potential risks of making significant changes. Effective refactoring improves long-term maintenance but requires a careful judgment about when and how to refactor.

### Recognizing Code Duplication: 
Code duplication is a common pitfall in programming that can lead to maintenance issues. Understanding how to identify duplicated logic among functions enables programmers to create a more efficient, DRY (Don’t Repeat Yourself) codebase.

### Managing Function Length: 
Long methods often indicate a lack of focus and can lead to reduced code clarity. A good practice is to keep functions concise, ideally within a size that allows for easier comprehension and debugging.

### Mitigating Technical Debt: 
By confronting problems through systematic refactoring rather than quick patches, developers can reduce technical debt. This proactive approach creates a healthier codebase that is less likely to require a complete rewrite in the future.

### Continuous Learning: 
Developers grow by creating heuristics based on experience with code smells, which brings to light their personal standards for code quality. This continuous improvement process enhances their coding capabilities over time.

### Intentional Refactoring Time: 
Developers should allocate specific time slots during their coding routine for refactoring. This practice encourages a sustainable development cycle and allows for constant code quality improvements without overwhelming projects with last-minute changes.

---


# Week 4
## Debugging From Ashley

The video discusses the apocryphal story of the first computer “bug,” which allegedly involved a moth that disrupted a computer in 1947, highlighting early computer science’s challenges and historical context. It introduces Grace Hopper, a pivotal figure in computer science, to illustrate the significant contributions of women in the field, despite historical biases. The video transitions into the broader concept of bugs in programming, defining them as small errors causing unexpected outcomes, and emphasizes the importance of good programming practices to mitigate bugs.

Good coding practices highlighted include the use of clear naming conventions, self-documenting code, modularity, encapsulation, and frequent commits. The speaker discusses debugging basics, advocating for a systematic approach reminiscent of the scientific method—studying the data, hypothesizing, conducting experiments, and refining the hypothesis based on findings. Tips for effective debugging include the use of logging and breakpoints, conditional breakpoints, and employing techniques like rubber ducking, which involves explaining the code to an imaginary ally to gain clarity on problems. Emphasis is placed on intentional programming and maintaining discipline through proper coding and documentation practices.
 
## Highlight From Video

### First Computer Bug Story
The accidental discovery of a moth in a computer in 1947 is humorously branded as the first computer bug.

### Grace Hopper’s Contribution
Grace Hopper is recognized as a key figure in computer science, despite historical biases against women in tech roles.

### Understanding Bugs
Bugs are defined as programming errors leading to unforeseen behaviors, underlining the necessity for good coding practices.

### Importance of Documentation
The use of self-documenting code and clear naming conventions can help streamline debugging efforts.

### Systematic Debugging
A scientific method-like approach is recommended for identifying and fixing programming bugs, stressing data analysis, hypothesis formation, and controlled experimentation.

### Effective Debugging Tools
Tools like console logs and IDE features, such as breakpoints, play a crucial role in the debugging process.

### Rubber Duck Debugging
Explaining code to a “rubber duck” is presented as a technique for revealing hidden assumptions and clarifying thinking around code problems.

---

## Key Insights

### Historical Context of Computer Science
The story of the first computer bug serves as a reminder of the historical challenges and pioneers in computer science, particularly illustrating how early computing was heavily intertwined with military funding and defense initiatives post-World War II.

### Bugs and Their Origin
While the 1947 moth story is entertaining, it underscores that the concept of debugging and identifying errors has roots that predate this anecdote, showcasing an evolving understanding of programming challenges.

### Good Programming Practices
Emphasizing coding conventions and modularity not only aids in debugging but positions coders to handle complex issues before they become problematic, laying groundwork for reduced errors in the long run.

### Bias in Representation
The video reveals that biases and underrepresentation in computer science have persisted over decades, prompting a need for ongoing awareness and proactive measures to celebrate contributions from diverse backgrounds.

### Commitment Culture
Regular commits allow for safer navigation of coding projects, as they provide checkpoints for developers to revert changes and avoid overwhelming layers of adjustments that could introduce new problems.

### Diagnostic Tools and Techniques
Novice programmers are encouraged to use both basic and advanced debugging tools, with a clear understanding that making informed choices about when and how to employ these tools greatly affects efficiency.

### Frequent Reflection
The rubber duck debugging technique pushes developers to explore their assumptions verbally, enhancing their understanding of the code in a collaborative yet self-reflective manner, thus tackling their own cognitive biases.

This comprehensive approach not only elucidates debugging concepts but also acknowledges the interplay between historical context, programming practices, and the continuous evolution of technology in fostering a more profound comprehension of computational systems.

## Bug Tracking 

The video introduces bug and issue tracking software by explaining the fundamentals of creating effective bug reports. A bug report is a detailed step-by-step account illustrating how to reproduce a specific software bug. It should focus on documenting a single bug with clear reproduction steps and expected results. Key aspects of a bug report include specificity, relevance, and clarity, as ambiguity can lead to miscommunication and unreproducible results.

Failures in bug reports often stem from a lack of specificity in titles, ambiguous reproduction steps, and confusion between user error and genuine bugs. To effectively report bugs, it’s crucial to conduct thorough checks to ensure that the issue is not a misunderstanding of the software’s design. Good bug reports consist of clear, atomic reproduction steps that avoid overwhelming detail yet focus on necessary actions to reproduce the bug.

## Highlight From the Video 

### Definition of Bug Report
A bug report is a documented process detailing how to reproduce a software bug, ideally focusing on one issue.

### Key Components
Proper bug reports include reproducible steps, expected results, and other relevant metadata like priority and version information.

### Reproducibility
Clear and precise reproduction steps are critical in both identifying edge cases and helping developers recreate and fix the issue.

### Common Mistakes
Failure to specify bug details, losing clarity in reproduction steps, and user misinterpretation of software functionality are frequent pitfalls in reporting.

### Roles in Bug Reporting
Bug reports come from various sources including QA teams, developers, and even end users, all of whom contribute to software quality.

### Popular Tools
Bugzilla, JIRA, Asana, and GitHub Issues are noted as key bug tracking tools, each having unique characteristics and levels of integration into the development process.

### Quality Assurance Importance
Emphasizing quality assurance’s role in creating bug reports, the video articulates the necessity of accurate documentation to enhance software quality.

---

## Key Insights

### Importance of Specificity
Bug reports must feature specific titles and steps; vague titles like “button does not work” hinder effective resolution and lead to confusion. Clear titles give immediate context to the issue, nudging developers toward solutions faster.

### Atomic Steps Matter
Each step in a bug report should be atomic and clear—this means breaking down actions into concise, understandable parts reduces the chance of interpretation errors and encourages successful bug reproduction.

### Edge Cases Complexity
Many bugs stem from unforeseen edge cases tied to user environments. Developers need to be aware of these nuances, which often complicate the reproduction of issues, highlighting the necessity of thorough testing across diverse scenarios.

### User Feedback Mechanisms
Allowing users to submit bug reports provides real-world data essential for developers but should be accompanied by guidelines to reduce vague submissions. User submissions can yield valuable insights about practical applications of software.

### Distinguishing User Error
It’s crucial to analyze whether a reported bug is actually a misunderstanding of the intended design. This distinction frequently shapes the debugging process and resource allocation for fixes.

### Tool Integration
Utilizing tools like JIRA or GitHub Issues not only streamlines bug reporting but also supports project management, improving workflow efficiency and team collaboration.

### Prioritization in Management
Understanding the severity and reproducibility of bugs allows teams to prioritize fixes effectively, ensuring critical user-facing issues are addressed promptly. This promotes a better user experience and aids in sustaining software integrity.


# Week 5
## Testing From Ashley

In this video lecture on software testing,Ashley delves into the fundamental concepts and techniques involved in testing software, emphasizing the importance of validation and verification. Software testing is presented as a vital practice that offers independent assessments of software quality, thus minimizing the risks of failure. The distinctions between validation (confirming that the software meets specified requirements) and verification (ensuring the software is built correctly) are highlighted. 

The lecture also explores the various levels and approaches to testing, ranging from unit testing, which focuses on individual components, to user interface testing, which examines how software interacts with users. The presenter discusses the necessity of running tests dynamically, emphasizing that runtime behavior can differ significantly from static analysis of code.

## Highlight From the Video

### Software Testing Basics
Software testing evaluates software quality through validation and verification.

### Dynamic Testing
Emphasizes the role of runtime behavior and dynamic testing in ensuring software runs correctly.

### Testing Levels
Distinguishes between unit tests, integration tests, and user interface tests, outlining their unique purposes.

### Testing Strategies
Discusses the significance of planning and the necessity of a structured testing approach.

### Error Tracing
Highlights the importance of tracing program execution to identify bugs and understand code behavior.

### Test-Driven Development (TDD)
Introduces TDD as a methodology where tests are created before the actual code, promoting better design and confidence.

### Continuous Integration
Covers how continuous integration practices ensure software stability and quality by automatically running tests on code push.

---

## Key Insights

### Validation vs. Verification
Understanding the distinction is crucial; validation ensures the software meets user needs, while verification checks code correctness against specifications. This clarity can lead to more effective testing strategies and fewer bugs.

### Unpredictable Inputs
Software interacts with various inputs that can be unpredictable. Testing should therefore include edge cases and potential user errors to ensure the system can handle a wide array of scenarios without failure.

### Automated vs. Manual Testing
While automated testing can run continuously and often, manual testing is essential for nuanced evaluations, especially in user-centric applications like video games, where real-world usage might reveal unique flaws.

### Importance of a Testing Plan
A well-defined testing plan is necessary to guide the testing process, ensuring all relevant scenarios are covered and that the tests remain meaningful and pertinent to the software’s objectives.

### Real-World Testing Failures
The case of the Mars Climate Orbiter illustrates how miscommunication and lack of thorough testing can lead to catastrophic failures, reinforcing the critical importance of rigorous software validation.

### Continuous Integration Benefits
Utilizing tools for continuous integration enhances collaborative software development by automatically running tests, which allows teams to identify issues early and streamline code deployment efforts.

### Unit Testing as a Foundation
Unit testing, focusing on small code units, is foundational for ensuring code integrity and establishing a robust software base that supports additional testing layers effectively.

The topics covered in this lecture illustrate the multifaceted nature of software testing and the various strategies that software engineers should employ to enhance code reliability and performance, underscoring a proactive approach to identifying and addressing potential software issues before they arise in live environments.


# Week 8 
## Functional User Requirement From Ashley
This Video, Elaborates on the concepts of functional requirements and user stories in the context of app development. The discussion emphasizes the importance of bridging the gap between user experience and technical implementation. Developers are encouraged to understand both perspectives—how users interact with the app and how the app is functionally structured from a programming and computer science viewpoint.

User stories are presented as a valuable tool for defining user-facing functionalities in a straightforward manner, typically written in natural language for clarity. These user stories facilitate team communication by providing a collective understanding of the app’s intended features. However, the speaker highlights the limitations of user stories, particularly their lack of specific technical details that are crucial for developers during implementation. Without addressing non-functional requirements such as performance, the team risks overlooking critical aspects of the app’s functionality.

## Highlights From Video

### Emphasis on User Experience
Understanding both user interaction and technical implementation is essential for developers.

### User Stories as Communication Tools
User stories help teams align their vision and clarify app functionalities.

### Limitations of User Stories
They often lack important technical details that guide developers during implementation.

### Role of Technical Design Documents
TDDs provide a high-level overview but may lose relevance during ongoing development.

### Functional Requirements Explained
They specify software features based on inputs and outputs, clarifying user expectations.

### Dynamic Documentation
Design documents are crucial at early development stages but become outdated as the coding progresses.

### Mixing Engineering Principles
Integrating software engineering practices into app development can enhance clarity without overwhelming teams with technical details.

---

## Key Insights

### Holistic Development Perspective
Developers should balance user interface design with a solid understanding of technical frameworks to create effective applications. Emphasizing both dimensions improves a product’s overall reliability and user satisfaction.

### Effective Communication through User Stories
Well-crafted user stories not only promote a shared understanding among team members but also serve as foundational elements for further technical documentation, such as functional requirements and TDDs.

### Lack of Technical Detail Can Hinder Execution
User stories that do not address performance or functional constraints can lead to misalignments in the development process, resulting in a suboptimal app experience and potential oversights in critical areas.

### The Importance of TDDs
By offering a structured overview of the app’s technological requirements, TDDs maintain clarity during early development stages, promoting a smoother transition from planning to execution while minimizing confusion.

### Relevance of Functional Requirements
Constructing functional requirements from user stories helps in outlining specific features and expected results, providing a roadmap for development that ensures user needs are addressed effectively.

### Documentation as a Living Resource
Recognizing that development documents may quickly become outdated necessitates a flexible approach to documentation that incorporates ongoing changes in the project and software iterations.

### Complex Features Require Detailed Attention
Focusing on intricate software components necessitates detailed planning through functional specifications, ensuring that all functionality is adequately captured and appropriately developed.


# Week 9
## Design Patterns
The video discusses the history and fundamental concepts behind design patterns, particularly in the context of object-oriented programming (OOP). It introduces these common solutions, termed “design patterns,” which have emerged to address well-defined programming problems, emphasizing their importance in software development. The concept was popularized in the early 1990s by a group of developers known as the “Gang of Four” through their book “Design Patterns: Elements of Reusable Object-Oriented Software.” They emphasized two principles: programming to an interface rather than an implementation and favoring object composition over class inheritance. The video explains how inheritance is a commonly used feature but can complicate code structures. It advocates for interfaces, which allow for a clean separation of contracts and implementations, thereby enhancing flexibility and reducing code duplication.

---
## Highlights

### Design Patterns are Well-Defined Solutions  
They provide recognized approaches to common programming issues in the object-oriented paradigm.

### Gang of Four  
This group of four developers popularized design patterns in the early '90s, significantly influencing modern programming practices.

### Key Principles  
“Program to an interface, not an implementation” and “favor object composition over class inheritance” are core ideas of effective design.

### Avoiding Complications  
Over-reliance on class inheritance can lead to complicated and brittle code structures.

### Importance of Interfaces  
Interfaces help decouple systems, allowing for shared contracts among different classes while maintaining clear boundaries.

### Three Categories of Design Patterns  
Creational, structural, and behavioral patterns guide developers in choosing the right pattern for their problems.

### Caution Against Anti-Patterns  
Design patterns may not always be beneficial and could lead to potential maintenance issues if misapplied.

---

## Key Insights

### Pattern Evolution in Software Development  
Design patterns represent a maturity in software design that allows developers to solve common problems more efficiently. They promote reusability, aiding in reducing costs and time spent on development. By adopting patterns, developers can leverage collective wisdom distilled into these codified solutions.

### Interface vs. Implementation Debate  
The principle of programming to an interface facilitates flexibility. It allows programmers to swap implementations without changing the code that relies on the interface, leading to enhanced maintainability in the long term. As systems evolve, interfaces can support transitions without significant rewrites.

### Risks of Inheritance  
Deep inheritance trees can complicate code and introduce difficulties in maintenance and understanding. This reliance on class inheritance can lead to complex and brittle code structures. Design patterns should foster flexibility and avoid rigid hierarchies.

### Object Composition as a Solution  
Object composition encourages developers to build complex functionality from simpler, reusable components. This can lead to clearer, more maintainable code and better separation of concerns within systems.

### Adaptability of Design Patterns  
While design patterns can enhance structure and organization in various programming environments, applying them in non-OOP contexts requires careful consideration. The evolution of programming languages continues to render some patterns either superfluous or unnecessarily complicated.

### Observer Pattern in Action  
The Observer pattern is highlighted as a significant behavioral design pattern that supports dynamic communication. It is especially useful in applications that respond to asynchronously generated events, such as user interactions in UI development, offering a robust way to manage state updates.

### Design Patterns vs. Anti-Patterns  
Understanding design patterns is crucial, but it’s equally important to identify anti-patterns—common mistakes made during the software development process. This awareness fosters better coding practices by preventing developers from repeating ineffective strategies. Engaging with local communities can help developers stay informed about best practices and emerging trends in their programming languages.

