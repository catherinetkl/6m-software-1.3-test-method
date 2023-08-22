## Brief

### Lesson Overview

We will be spending the first hour to learn about software testings, and next 2 hours on quick JavaScript lesson and assignment. At the end of the assignment, learners will see a short demo on unit test within the [assignment](./assignment) folder.

Command to run test:

```sh
npm run test 
```

If you face issue running `jest` in the `devDependency`, a quick remedy is to run `npm i -g jest` first.

> Note for instructors
> - Run all `.js` files with `node` in the Terminal.
> - While running JS code, use debugging terminal to visually guide learners how codes are executed.

---

## Part 1 - Software Development Life Cycle

<img src="./assets/sdlc.png" />

Source: https://www.javatpoint.com/software-engineering-software-development-life-cycle

1. *Requirement* Analysis - Gathering the business and technical requirements.
1. *Defining* - Defining the functional and non-functional requirements.
1. *Designing* - Translating the functional requirements into workable tasks.
1. *Coding* - Writing code a.k.a. development phase.
1. *Testing* - Ensuring the outcome of development aligns with the defined requirements.
1. *Deployment* - Going live into production.
1. *Maintenance* - Monitoring systems health and fix errors when arises.

---

## Part 2 - Software Testing Methods

<img src="./assets/test-diagram.png" />

### Functional Testings

1. *Unit Test* - An isolation testing targeting at the smallest piece of logic in the software.
2. *Integration Test* - Testing multiple software modules together (with all the components) as a group, making sure that everything works. 
3. *Acceptance Test* - Testing the functionality of the software by end users before launch.

### Non-functional Testings

1. *Performance Test* - A non functional test to determine the stability, speed, responsiveness and resilience of the system.
    1. Load Test - Simulate an increasing amount of traffics/requests sent to the system.
    1. Stress Test - Determine the peak load and/or how much requests the system can receive.
    1. Endurance Test - Determine the behaviour of the system at the peak load over time.
1. *Security Test* -
    1. Dependency Vulnerabilities - Scanning for vulnerabilities introduced by dependencies.
    1. Secrets & Data Storage Strategy - Determine how secure are secrets and sensitive data being stored.
---

## Part 3 - Group Discussion

Understanding Part 1 and Part 2, learners will be grouped in a team of 3 or 4 to research (google), discuss and fulfil the blanks in the following table. Learners may simple use google docs for this.

|The Test|When? (SDLC)|How are they performed?|
|----|----|---|
|Unit Test|5|A unit test comprises three stages: planning, writing test cases and performing the unit test itself. In the first step, developers or QA professionals prepare and review the unit test. In the next step, they write test cases and scripts. In the third step the code is tested.|
|Integration Test|5|Integration tests are performed during the Testing phase of the software development life cycle. They involve testing the interactions and interfaces between different components or modules of the software to ensure that they work together as expected. This is achieved by combining the individual components and testing their interactions to identify any issues or inconsistencies that might arise when they are integrated.|
|Acceptance Test|5|Acceptance tests are conducted during the Testing phase of the software development life cycle. These tests are designed to determine whether the software meets the specified business requirements and is ready for deployment. They are typically performed by stakeholders, end-users, or quality assurance teams, and involve simulating real-world scenarios to validate the software's functionality, performance, and overall suitability for its intended use.|
|Performance Test|Enter 1 to 7|3 sentences max|
|Security Test|Enter 1 to 7|3 sentences max|

> Bonus Question: Are there any other forms of software/system testings that are not listed in this lesson?

### Example
|The Test|When? (SDLC)|How are they performed?|
|----|----|---|
|Security Test|5,6,7 and 7|It can be done with automation, engage testing companies, or AI|

---

## Part 4 - Data Types in JavaScript

The primitive data types of JavaScript are:
- number
- string
- boolean
- null
- undefined
- symbol (advanced, not covering)

The composite types are:
- object
- array

Check out [this](./src/data-types.js) JS file.

---

## Part 5 - Arrays

Arrays consist of indices and values.

<img src="./assets/array.jpeg" />
Source: [Arrays](https://www.geeksforgeeks.org/c-sharp-arrays/)

Look at the basic use of array [here](./src/arrays.js).

---

## Part 6 - Objects

Objects are made up with key-value pairs that represent properties and values. In some programming languages, the name of the data structure is "Dictionary". In JavaScript, they are called objects.

Look at the basic use of object [here](./src/objects.js).
