# CS-320-10489-M01-Software-Test-Automation-QA

# Reflection

# How can I ensure that my code, program, or software is functional and secure?

Ensuring functionality and security starts with comprehensive unit testing. In this course, I developed JUnit test classes for each service component, creating tests that validated both expected behavior and edge cases. I used assertions to verify that methods performed correctly and threw appropriate exceptions when given invalid input. For security, I implemented input validation in my service classes, checking for null values, proper string lengths, and valid date ranges before accepting data. Code coverage analysis helped me identify untested paths, and I aimed for high coverage percentages to catch potential bugs early. I also followed the principle of failing fast—rejecting invalid data immediately rather than allowing it to propagate through the system.

# How do I interpret user needs and incorporate them into a program?

Interpreting user needs begins with carefully analyzing requirements documents. For the Grand Strand Systems mobile application, I broke down each requirement into specific, testable criteria. For example, when the requirement stated that contact IDs must be non-null and no longer than 10 characters, I translated that into validation logic and corresponding unit tests. I created detailed checklists to ensure every requirement was addressed. I also considered the user experience—what would happen if someone tried to create a contact with invalid data? By throwing clear exceptions with descriptive messages, I made the system's behavior predictable and debuggable. Testing each requirement individually ensured that user needs were met before moving forward.

# How do I approach designing software?

My approach to software design is iterative and component-based. I break complex systems into smaller, manageable pieces and build each component thoroughly before integration. For this project, I started with the data objects (Contact, Task, Appointment), ensuring they had proper validation and immutability where needed. Then I built the service layers that managed collections of these objects. At each step, I wrote unit tests before or alongside the implementation code, following test-driven development principles. This approach catches errors early when they're easier to fix. I also prioritize code readability, using clear variable names, adding comments to explain complex logic, and organizing code into logical sections. Good design means the next developer—or future me—can understand and maintain the code easily.
Project Artifacts

# This repository contains the following artifacts from CS 320:
# Project One - Unit Testing

    Contact.java - Contact data object with validation
    ContactService.java - Service class for managing contacts
    ContactTest.java - JUnit tests for Contact class
    ContactServiceTest.java - JUnit tests for ContactService class

# Project Two - Testing Strategy

    Summary_and_Reflections_Report.pdf - Analysis of testing approaches and strategies

These artifacts demonstrate my ability to create comprehensive unit tests, analyze software testing approaches, and apply appropriate testing strategies to meet requirements.
