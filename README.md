# MyStudyPath-
This study path is released under the CC BY-SA 4.0 license
Introduction

Welcome to this study path, or if you like, the learning path. Is a path about software development practices and design principles. It's open and freely accessible to everyone who wants to dig into topics like Clean Code, Test-Driven Development, Refactoring, Clean Architecture, Legacy Code, Domain-Driven Design, Microservices, and much more.

The materials are all organized in sections based on specific topics. There is no order to follow. You can skim through all the sections, look for anything specific, follow only a few sections, or just start reading from the very beginning to the end. It's your choice!

I am willing to keep this study path always updated, and I would invite you to contribute to this project by submitting any material you believe will improve it.

Why this study path? Few years ago I worked as a mentor for an intern in Agile Software Development, and I wanted to provide a clear path to follow. At that time, the study was covering Clean Code, Test-Driven Development, and other few topics. By the time, with the support of other people, we enhanced the study path with more and more content!

Enjoy!
Getting Started

    Get familiar with the Pomodoro Technique (read the paper)
    Read the Manifesto for Agile Software Development
    Read the Principles behind the Agile Manifesto
    Read the Manifesto for Software Craftsmanship

Session 1: SOLID and Clean Code

    Watch Core Design Principles for Software Developers
    Read the SOLID principles
        SRP: Single Responsibility Principle
        OCP: Open-Closed Principle
        LSP: Liskov Substitution Principle
        ISP: Interface Segregation Principle
        DIP: Dependency Inversion Principle
    Exercise: Look at the Racing Car Katas
        Try to find where the SOLID principles are violated
    Read the Clean Code
        Chapter 1: Clean Code
        Chapter 2: Meaningful Names
        Chapter 3: Functions
        Chapter 6: Objects and Data Structures
        Chapter 7: Error Handling
        Chapter 10: Classes
    Read The Pragmatic Programmer
        Chapter 2: A Pragmatic Approach
        Chapter 5: Bend or Break
        Chapter 6: While You Are Coding
    Read The Art of Enbugging: Tell, don't ask / Law of Demeter
    Read YAGNI

Session 2: Test-Driven Development

    Read TDD by example
        Study the Part I: The Money Example
        Exercise: Try to repeat it with a programming language at your choice.
    Read Growing Object-Oriented Software, guided by tests
        Chapter 1: What is the point of Test-Driven Development?
        Chapter 2: Test-Driven Development with Objects
        Chapter 4: Kick-Starting the Test-Driven Cycle
        Chapter 5: Maintaining the Test-Driven Cycle
    Unit Tests
        Read Chapter 9: Unit Tests of Clean Code
        Watch The Clean Code Talks - Unit Testing
        Read Effective Unit Testing
            Part 1: Foundations
            Part 2: Catalog
    Read desirable properties of tests
        Watch the video playlist

Session 3: Refactoring

    Watch Workflows of Refactoring
    Read Refactoring: Improving the design of existing code
        Chapter 1: Refactoring, a First Example
            Try to repeat the example code
        Chapter 2: Principles in Refactoring
        Chapter 3: Bad Smells in Code
    Exercise: Try to find and refactor the code smells in these Code Katas:
        Tennis Refactoring Kata
        Gilded Rose Kata
        What Code Smells you have found?
            What steps you followed to remove them?
            What difficulties you have faced?

Session 4: Working with Legacy Code

    Read Working Effectively with Legacy Code
        Chapter 1: Changing Software
        Chapter 2: Working with Feedback
        Chapter 4: The Seam Model
        Chapter 8: How Do I Add a Feature ?
        Chapter 13: I Need to Make Changes, but I Don't Know What Tests to Write
        Chapter 25: Dependency-Breaking Techniques
    Read Working Effectively with Legacy Tests
    Exercise: Try the Gilded Rose Kata
        Add code coverage
        Add the new feature
        Refactor the code
    Watch how other tackled the Gilded Rose Kata:
        Watch All the Little Things
        Watch "Writing test cases using Approval Tests" (Part I, Part II, Part III)
    Watch Testing and Refactoring Legacy Code
        Exercise: Try to repeat the Code Kata
    Read more about Approval Testing and some examples:
        Characterization Testing
        Mutation Testing
        Golden Master and Sampling
            How Not To Write Golden Master Tests
        Exercise: Try to test and refactor the Ugly trivia game
            Which is the approach you prefer to apply? Why?
    Watch Surviving a legacy codebase: tactics and tools
        Read the Slides of the talk
        Have access to the example code for further practice

Session 5: Testing, Design and Test-Driven Development

    Watch The deep synergy between testability and good design
    Watch How to Write Clean, Testable Code
    Watch TDD and Software Design
    Read Good Design is Easily-Learned
    Exercise: Try to learn and repeat these Code Kata autonomously
        The Bowling Game Kata
        The Roman Numerals Kata
    Watch Unit Testing
    Read Growing Object Oriented Software, Guided by Tests
        Chapter 6: Object-Oriented Style
        Chapter 7: Achieving Object-Oriented Design
        Chapter 8: Building on Third-Party Code
    Read Clean Code
        Chapter 8: Boundaries
    Watch The Magic Tricks of Testing
    Read Mocks Aren't Stubs
    Exercises:
        Try the String Calculator Kata
            With interactions
        Try the Game Of Life Kata
        Try the Tic Tac Toe Kata

Session 6: Practice with a new Programming Language

Principles and Practices are not dependent on any particular programming language, rather they act as support or enabler to learn and get comfortable with programming languages and tools we never used before.

Now that you have learned something about the good principles and practices of software development, try to grab a new programming language which you never used before and try to repeat some of the Code Katas you already have done previously:

    Fizz Buzz Kata
    The Bowling Game Kata
    String Calculator Kata
    The Roman Numerals Kata
    Game Of Life Kata
    Tic Tac Toe Kata
    Opening Hours Kata
    Racing Car Katas
    Repeat the Money Example of TDD by Example
    Gilded Rose Kata

If you are looking for more Code Katas to learn and practice with your new programming language, try to give a look at Kata-Log.
Session 7: The Clean Architecture

    Read Hexagonal Architecture
    Read The Onion Architecture
    Read The Clean Architecture
    Watch Clean Architecture and Design
    Watch Lean Agile Scotland "Crafted Design"
    Watch Jax London 2014 "Crafted Design"
    Watch Spring I/O 2019 Clean Architecture
    Exercises:
        Try the Social Networking Kata
        Try the Greeting Service Kata
    Once you have done one of the previous Code Kata, try to build and deploy your application
        Read The Twelve-Factor App
        Publish the code on a GitHub repository
        Setup a CI environment (e.g. Travis/CircleCI/CodeShip)
        Deploy your application automatically (e.g. Heroku)
        Write a suite of tests to check the deployed application is working as expected
    Take a look at this reference implementation on Clean Architecture

Session 8: Domain-Driven Design

    Watch Tackling Complexity in the Heart of Software
    Read Domain-Driven Design Quickly
        Chapter 1: What Is Domain-Driven Design
        Chapter 2: The Ubiquitous Language
        Chapter 3: Model-Driven Design
        Chapter 4: Refactoring Toward Deeper Insight
        Chapter 5: Preserving Model Integrity
    Read DDD: Putting the Model to Work
    Read How to write a Repository
    Watch DDD and Microservices: At last, some boundaries!
    Recommended readings:
        Domain-Driven Design: Tackling Complexity in the Heart of Software
        Implementing Domain-Driven Design
        Domain-Driven Design Reference: Definitions and Pattern Summaries

Session 9: Microservices

    Read Microservices: A Definition of This New Architectural Term
    Watch Microservices
    Watch Principles Of Microservices
    Read Microservice Trade-Offs
    Read Microservice Architecture: Aligning Principles, Practices, and Culture
        Chapter 1: The Microservices Way
        Chapter 2: The Microservices Value Proposition
        Chapter 3: Designing Microservice Systems
        Chapter 4: Establishing a Foundation
        Chapter 5: Service Design
    Read Building Microservices: Designing Fine-Grained Systems
        Chapter 1: Microservices
        Chapter 2: The Evolutionary Architect
        Chapter 3: How to Model Services
        Chapter 4: Integration
        Chapter 5: Splitting the Monolith
        Chapter 6: Deployment
        Chapter 7: Testing
        Chapter 8: Monitoring
        Chapter 11: Microservices at Scale
        Watch the Book Reading Club (part I - part II - part III)
    Watch Practical Considerations For Microservice Architecture
    Watch Microservices Antipatterns
    Read Seven Microservices Anti-patterns
    Transactions and consistency in distributed systems
        Watch Using sagas to maintain data consistency in a microservice architecture
        Watch Applying the Saga Pattern
    Access to more examples and resources

Session 10: Further topics

    Simple Design
        Read Beck Design Rules
        Read Emergent Design
        Read The Four Elements of Simple Design
        Read Putting An Age-Old Battle To Rest
        Read Chapter 12 of Clean Code: Emergence
    Watch Outside-in TDD (part I - part II - part III)
    Read TDD by example
        Patterns for Test-Driven Development
    CQRS and Event Sourcing:
        Watch CQRS and Event Sourcing
        Watch CQRS with Erlang
        Watch A Decade of DDD, CQRS, Event Sourcing
        Read CQRS Journey
    Exercises:
        Try the Salary Slip Kata
        Try the Bank Account Kata
            Try to implement a variant using a CQRS/ES approach

Recommended Readings

This section provides a list of recommended books readings that have not been mentioned directly in this study path, but of significant importance.

    The Nature of Software Development
    Extreme Programming Explained: Embrace Change (2nd Edition)
    The Agile Samurai: How Agile Masters Deliver Great Software
    Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation
    Release It!: Design and Deploy Production-Ready Software
    Beyond Legacy Code: Nine Practices to Extend the Life (and Value) of Your Software
    The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win

my study path 
