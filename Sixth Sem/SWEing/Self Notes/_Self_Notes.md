# <center>Software Engineering

## [In A Single Video](https://www.youtube.com/watch?v=NlLM3sVF8wY)

# **#1 Introduction**

Software Engineering is the process of designing, developing, testing, and maintaining software. It is a systematic and disciplined approach to software development that aims to create high-quality, reliable, and maintainable software.

> **First `38` pages of the pdf**

<br>
<br>

## **#2 SDLC & Software Development Models**

## <u> SDLC </u>

> **PDF Page: `39-46`**

## <u> SDLC Models</u>

selection of correct development model plays an important role in overall quaaity of s/w

> _We have `Waterfall` and `Spiral` Model in the syllabus only_ > ![Models](image.png)

<!-- All models ony by one -->

### 1. Waterfall model

> **PDF Page: `47-54`**

![ad and dis advantages](image-1.png)

**_When to Use Waterfall Model?_**

- `Well-understood Requirements`: Before beginning development, there are precise, reliable, and thoroughly documented requirements available.
- `Very Little Changes Expected`: During development, very little adjustments or expansions to the project’s scope are anticipated.
- `Small to Medium-Sized Projects`: Ideal for more manageable projects with a clear development path and little complexity.
- `Predictable`: Projects that are predictable, low-risk, and able to be addressed early in the development life cycle are those that have known, controllable risks.

### 2. Iterative Waterfall model

It allows for improvements and changes to be made at each stage of the development process, instead of waiting until the end of the project. The Iterative Waterfall Model provides **feedback** paths from every phase to its preceding phases, which is the main difference from the classical Waterfall Model.

![img](image-2.png)

### 3. V Shaped model

The V-model is an SDLC model where execution of processes happens in a sequential manner in a V-shape. It is also known as **Verification and Validation model**.

- The V-Model is an extension of the waterfall model
- The testing is associated with every phase of development cycle
- there are **Verification phases** (Requirement Analysis, Sys Design, Architectural Design, Module Design) on one side of the ‘V’ and **Validation phases** on the other side. The Coding Phase joins the two sides of the V-Model.

> ![alt text](image-4.png)

![alt text](image-5.png)

> verification Phases

`Requirement Analysis` - Gather and analyze user needs.

`System Design` - Define overall system architecture and functionality. (House design)

`Architecture Design` - Plan system structure, modules, and interactions. (a specific Floor design)

`Module Design` - Design individual software components or modules. (Room design)

> Coding Phase

Implement the designed system using programming languages.

> Validation Phases

`Unit Testing` - Validate the functionality of individual modules.

`Unit Test Design` - Create test cases for individual modules.

`Integration Testing` - Verify communication between integrated modules.

`Integration Test Design` - Plan tests to check module interactions.

`System Testing` - Ensure the system meets technical specifications.

`System Test Design` - Prepare test cases to validate the complete system.

`Acceptance Testing` - Verify if the system meets business and user requirements.

`Acceptance Test Design` - Define test cases for user validation.

![alt text](image-6.png)

### 3. Prototype model

> PDF page: 54-60

    What is Software Prototyping?

    Prototype is a working model of software with some limited functionality. The prototype does not always hold the exact logic used in the actual software application

![alt text](image-7.png)

### 4. Incremental Process Model

> PDF page: `70-72`

First, a simple working system implementing only a few basic features is built and then that is delivered to the customer. Then thereafter many successive versions are implemented and delivered to the customer until the desired system is released.
(Eg: s/w updates)

> ![alt text](image-8.png)

![alt text](image-10.png)

### 5. Evolutionary Development Model

in Incremental Process Model the SRS document is defined there after the development process starts, oncec starts there is no feedback, but here has..

> PDF page: `68-69`

### 5. Spiral Model

The Spiral Model in software engineering is a risk-driven process model used to guide software development projects. It combines elements of both iterative and waterfall models, emphasizing risk management and incremental development. The model is particularly useful for large, complex, and high-risk projects where it’s important to carefully consider potential risks throughout the development process.

![alt text](image-11.png)

**Phases in Each Spiral**: Each cycle or iteration of the spiral typically includes the following four phases:

- **Planning**: Determine goals, objectives, and requirements for the next iteration, and set priorities.

- **Risk Analysis**: Identify and evaluate risks, such as technical challenges, resource constraints, or changes in user requirements. This phase helps in deciding how to proceed in the next cycle.

- **Engineering**: Perform development tasks (design, coding, and testing). At the end of each spiral, a working prototype or the actual product may be produced.

- **Evaluation**: At the end of each iteration, the progress is evaluated by stakeholders to decide whether to proceed with the next spiral, make adjustments, or halt the project.

> PDF page: `64-67`

### 5. RAD (Rapid Application Development) Model

> PDF page: `61-63`

[RAD VS SDLC](https://www.geeksforgeeks.org/software-engineering-rad-model-vs-traditional-sdlc/)

<!-- Agile dev -->

### 6. Agile (Also a SDLC model)

Agile is a way of developing software that focuses on **flexibility**, **teamwork**, and **continuous improvement**. Instead of planning everything in advance and working on a project for months before showing results, Agile **breaks the project into small parts (called `Iterations`)**. Each iteration usually lasts 1-4 weeks, and after each one, the team shows what they have built, gets feedback, and makes improvements.

![alt text](image-12.png)

### Key Principles of Agile

Agile follows the **Agile Manifesto**, which prioritizes:

- **Individuals and interactions over processes and tools:**
  Agile emphasizes the importance of human collaboration and communication

- **working software over comprehensive documentation:** Agile prioritizes delivering tangible, working software over exhaustive documentation

- **Customer collaboration over contract negotiation:** Agile promotes active involvement of customers and stakeholders throughout the development process.

- **Responding to change over following a plan:** Agile embraces change as a natural part of the development process.

### Agile frameworks

- Scrum – Uses short sprints (1-4 weeks) and daily stand-up meetings.

- Kanban – Uses a visual board to manage tasks and workflow.

- Extreme Programming (XP) – Focuses on coding best practices and frequent testing.

All of these follow Agile principles but have different ways of organizing work. 🚀

### 7. scrum model

Scrum is a popular Agile framework used for software development. It helps teams work in small, time-boxed cycles called `sprints` (usually 1-4 weeks long). At the end of each sprint, a working part of the software is delivered, tested, and improved based on feedback.

### Key Roles in Scrum:

- `Product Owner` – Decides what needs to be built (sets priorities).
- `Scrum Master` – Ensures the team follows Scrum rules and removes obstacles.
- `Development Team` – Builds the software and delivers features in sprints.

![alt text](image-13.png)

- **backlog** is a to-do list of all the tasks and features that need to be developed.

- **Product Backlog** – A list of all features, fixes, and improvements for the whole project.

- **Sprint Backlog** – A list of tasks selected from the product backlog to be completed in the current sprint.

- **Sprint Retrospective** - is a meeting held at the end of a sprint in Scrum. The team discusses:
  What went well ✅
  What went wrong ❌
  What can be improved 🔄

---

<br>

# <center> software Requirement

Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC) where the goal is to understand what the users need from a software system. It's the process of gathering, analyzing, documenting, and validating the requirements of a software project.

### Purpose of Requirement Analysis

- To identify what the users want the system to do.

- To avoid misunderstandings between clients and developers.

- To set the **foundation** for design, development, and testing.

- To ensure the final product meets the business goals and user needs.

### Stages of Requirement Analysis

![alt text](image-14.png)

1. **Draw a Context Diagram**

   - Shows the system’s boundary and its interaction with external entities (users, other systems).

   - Helps identify inputs and outputs.

2. **Develop Prototypes**

   - Create mock user interfaces or system flows.

   - Helps stakeholders visualize the system and give
     feedback early.

3. **Model Requirements**

   - Use tools like Use Case Diagrams, DFDs, or ER Models.

   - Makes complex requirements easier to understand and analyze.

4. **Finalize Requirements**

   - Confirm all requirements are clear, complete, and agreed upon.

   - Prepare the final Software Requirements Specification (SRS) document.

## Requirements Types - Food Delivery App

### 1. Functional Requirements (What the system should do)

These are the **specific features or functions** the app must provide.

**Examples:**

- Users can **search for restaurants** and food items.
- Users can **place an order** and make **online payment**.
- The app should **track order delivery status** in real-time.
- Delivery partners can **accept or reject** delivery requests.
- Admin can **add or remove** restaurants from the system.

---

### 2. Non-Functional Requirements (How the system should behave)

These define **quality attributes**, **performance**, or **constraints** of the system.

**Examples:**

- The app should **load within 3 seconds** on mobile devices.
- Must support **up to 1 million users concurrently**.
- Must provide **secure payment gateway** with **encryption**.
- The UI should be **easy to use** and **accessible**.
- System should have **99.9% uptime**.

---

### 3. Domain Requirements (Specific to the industry or field)

These are requirements based on **rules, standards, or needs** of the domain — here, the **food delivery industry**.

**Examples:**

- Must support **multiple tax rates** (GST, VAT) depending on region.
- Must **comply with food safety regulations**.
- Allow **restaurant-specific delivery hours** and **menu customization**.
- Integrate with **restaurant POS systems** for order sync.

---

![alt text](image-15.png)

## Structured Analysis

**Structured Analysis** is a **traditional method** in software engineering used to **analyze and model system requirements** in a **clear, logical, and graphical way**.

---

### ✍️ Key Points:

- Focuses on **what** the system should do, not how.
- Uses **diagrams** like:
  - **Data Flow Diagrams (DFD)**
  - **Entity-Relationship Diagrams (ERD)**
  - **State Transition Diagrams**
- Helps **break down complex systems** into smaller, understandable parts.
- Often used during the **requirement analysis phase** of SDLC.

---

### ✅ Example:

For a **Library Management System**, structured analysis might include:

- A **DFD** showing how users borrow books.
- An **ER diagram** of books, members, and transactions.

> Expolore the tools in PDF-1 : 78 [imp]

![alt text](image-16.png)

This diagram represents the **Structured Analysis** method used during the **Requirement Analysis** phase of system development.

---

## 🧩 Components in the Diagram

### ✅ 1. Information Gathering Tools

These tools are used to collect system requirements from stakeholders. Examples include:

- Interviews
- Questionnaires
- Observations
- Document Analysis

Collected information is then used in various modeling techniques.

---

## 🔁 2. Analysis & Modeling Techniques

These tools help structure and analyze the gathered information:

- **Data Flow Diagram (DFD)**  
  Visualizes how data flows within the system (processes, data stores, sources/sinks).

- **Decision Tree**  
  A graphical representation of decisions and their outcomes.

- **Decision Tables**  
  A tabular method for representing complex decision logic.

- **Structured Query**  
  Organized representation of data queries (often related to databases).

- **Pseudo Code**  
  A simplified, human-readable way to describe logic and processes before actual coding.

---

## 📦 3. Data Organization

The purpose of all the above tools is to **organize** the collected and analyzed data. This structured information serves as a foundation for the system's design and development.

## DFD

​A Data Flow Diagram (DFD) is a visual tool used in system analysis to depict how data moves through a system. It illustrates the flow of information, the processes that transform data, data storage points, and the external entities interacting with the system

### Components of a DFD

- `Processes`: Represented by `circles` or rounded rectangles, processes show the transformation of data within the system.​

- `Data Stores`: Depicted as `open-ended rectangles` or `parallel lines`, data stores indicate where data is held for later use.​

- `Data Flows`: `Arrows` that illustrate the direction and movement of data between processes, data stores, and external entities.​

- `External Entities`: `Squares` or rectangles that represent outside systems or actors that interact with the system, such as users or other systems.

![alt text](image-18.png)

## Data Flow Diagram (DFD) – Levels and Types

### 🧭 Types of DFD

### 1. **Logical DFD**

- Focuses on **what** the system does.
- Shows **business operations**, **data flow**, and **process logic**.
- Doesn’t include technical details like database names, devices, or software.

**Example:**
A logical DFD for a Library System might show:

- Processes: Register Member, Issue Book, Return Book
- Data Stores: Book List, Member Info
- Entities: Member, Librarian

### 2. **Physical DFD**

- Shows **how** the system is or will be implemented.
- Includes hardware, software, files, people, and systems involved.
- Useful for system designers and developers.

**Example:**
A physical DFD of the same Library System might show:

- MySQL database storing book info
- RFID scanners as input devices
- Web interface for book searching

---

### 🔢 Levels of DFD

### **Level 0: Context Diagram**

- The **highest-level** DFD (also called a context diagram).
- Shows the **entire system** as a single process.
- Shows **external entities** and **major data flows**.

**Example (Library System):**

[Member] --> (Library System) --> [Book Info]

### **Level 1 DFD**

- Breaks the Level 0 process into **sub-processes**.
- Shows **main system functions** and **data stores**.
- More detail than the context diagram.

**Example:**

[Member] --> (Register Member) --> (Issue Book) <--> [Book DB] --> (Return Book)

### **Level 2 DFD**

- Breaks a Level 1 process into **even smaller sub-processes**.
- Offers **greater detail**, showing specific actions and data interactions.

**Example:**
Process (Issue Book) from Level 1 could break into:

- Check Book Availability
- Verify Member Status
- Update Book DB
- Record Transaction

### [Watch This Video](https://youtu.be/sqCwE0SLTuw?si=a2sUnrFpZfHA9Ul9)

## Data Dictionary

Data Dictionary is a centralized repository that contains definitions and descriptions of all data elements used in a system. It's essentially a catalog of data that provides detailed information about each data item, helping ensure consistency and clarity across the project.

![alt text](image-19.png)

### Why It’s Important in Requirement Analysis:

- Clarifies Data Requirements:

  - Clearly defines all data elements needed by the system.

- Supports Data Flow Diagrams (DFDs):

  - Every data item flowing in DFDs should be described in the data dictionary.

![alt text](image-20.png)

### Purpose of a Data Dictionary:

- Maintain consistency in data naming and usage.
- Facilitate communication among developers, analysts, and stakeholders.
- Serve as a reference during system design, development, and maintenance.

## Decision Tree

A Decision Tree is a tree-like model used for decision-making, where:

- Each internal node represents a decision/test on an attribute.
- Each branch represents an outcome of the decision.
- Each leaf node represents a final decision or result.

It is used to map out different possible outcomes based on a series of conditions or choices.

### Scenario (Requirement):

A user can log in only if:

- The username exists in the system.
- The password is correct.
- The account is not locked.
- If two-factor authentication (2FA) is enabled, it must also pass.

### decision tree rep

```pgsql
                  Is username valid?
                   /            \
                No              Yes
               /                  \
         Show error        Is password correct?
                               /        \
                             No          Yes
                            /              \
                      Show error     Is account locked?
                                          /     \
                                       Yes       No
                                      /            \
                          Show "Account locked"   Is 2FA enabled?
                                                     /      \
                                                  No         Yes
                                                 /             \
                                            Allow login     Is 2FA correct?
                                                               /     \
                                                             No       Yes
                                                            /           \
                                                  Show 2FA error    Allow login
```

**Root Node: The first decision point.**

## Decision Table

A decision table is a structured way to represent `conditions` and `actions` for all possible combinations, especially useful when the logic gets complex.

![alt text](image-21.png)

### Conditions:

c1: Is username valid?

c2: Is password correct?

c3: Is account locked?

### Actions:

a1: Show "Invalid username"

a2: Show "Incorrect password"

a3: Show "Account locked"

a4: Allow login

![alt text](image-22.png)

### Rule Breakdown:

- Rule 1: Invalid username → Show a1.
- Rule 2: Valid username, wrong password → Show a2.
- Rule 3: Valid username/password, but account locked → Show a3.
- Rule 4: All conditions valid → Allow login (a4).

## Structured Query / Structurerd English

Structured English is a pseudo-code style of writing, that combines natural language (English) with programming logic structures.

It's used during system analysis to clearly define process logic without needing actual code.

used to describe how processes work in a system.

### Characteristics

- Uses simple, clear English.

- Incorporates logic keywords like:

  - `IF`, `THEN`, `ELSE`
  - `WHILE`, `FOR`, `DO`
  - `CASE`, `REPEAT`, etc.

- Doesn't require programming knowledge to understand.

- Easy for both technical and non-technical stakeholders to read.

### Example

```
IF customer type is 'Premium' THEN
    discount = 20%
ELSE IF customer type is 'Regular' THEN
    discount = 10%
ELSE
    discount = 0%
END IF
```

## Psudo Code :

Pseudocode is an informal, high-level description of an algorithm or process written in plain English (or any natural language) with a programming-like structure.

It doesn’t follow any specific syntax like a programming language but **follows logical steps that can later be translated into real code**.

more close to programming

- Written in a format that looks like code but isn’t.
- Uses logic keywords
- Shows the sequence, decision-making, and loops.

### Example : Find the largest of three numbers

```text
START
INPUT A, B, C

IF A > B AND A > C THEN
    PRINT "A is the largest"
ELSE IF B > C THEN
    PRINT "B is the largest"
ELSE
    PRINT "C is the largest"
END IF

END
```

### Sum of first N pos number

```text
START
INPUT N
SET sum = 0

FOR i = 1 TO N DO
    sum = sum + i
END FOR

PRINT sum
END
```

| Feature            | Structured English            | Pseudocode                        |
| ------------------ | ----------------------------- | --------------------------------- |
| Audience           | Analysts, stakeholders        | Developers, computer scientists   |
| Language Style     | Plain English + logic         | Programming-style logic           |
| Usage              | Process specification in DFDs | Algorithm design                  |
| Syntax             | No syntax rules               | Semi-formal, consistent structure |
| Conversion to Code | Not direct                    | Easy to convert into code         |

# Requirement Engineering

Requirement Engineering (RE) is the process of **collecting**, **analyzing**, **documenting**, and **managing** the `needs and requirements `of a software system from stakeholders.

> It’s how we understand what the user wants and turn it into clear instructions for developers.

## Phases of Requirement Engineering Process

> Notes : page 85

![alt text](image-23.png)

### 1. F**easibility Study**

Check if the project is practically and economically possible

Types of feasibility:

- `Technical`: Can we build it with available tech?
- `Economic`: Is it cost-effective?
- `Operational`: Will users accept and use it?
- `Schedule`: Can we finish it on time?

### 2. R**equirement Elicitation** (Gathering)

Gather requirements from users and stakeholders

Techniques: Interviews, surveys, brainstorming, observation

### 3. R**equirement Analysis**

Study requirements and resolve conflicts in the gathered requirements

### 4. **Requirement Specification**

Write a clear and detailed document

Usually results in an SRS (Software Requirements Specification)

### 5. **Requirement Validation**

Check: Are these requirements correct and complete?

Reviews, walk-through

### 6. **Requirement Management**

Track changes to requirements during development

Keep everything updated and controlled

# Feasibility Study :

> page : 91

---

# Cost-Benefit Analysis

Cost-Benefit Analysis (CBA) in Software Engineering is a systematic process to evaluate the strengths and weaknesses of alternatives in order to determine the best approach with the highest return on investment (ROI). It helps in decision-making by comparing the costs involved in a software project against the expected benefits.

It’s a technique to:

- Estimate costs (time, resources, money)
- Estimate benefits (revenue, efficiency, user satisfaction)
- Compare both to make informed decisions

![alt text](image-24.png)

### Components of CBA

| Component    | Description                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------- |
| **Costs**    | - Development cost<br>- Hardware/software purchases<br>- Staff salaries<br>- Maintenance & support<br>- Training |
| **Benefits** | - Revenue gain<br>- Time savings<br>- Increased productivity<br>- Improved quality<br>- Competitive advantage    |

### Example Scenario

Suppose you're considering building an internal tool to automate reporting tasks.

- Cost:

  - Development: $20,000
  - Maintenance: $2,000/year

- Benefit:

  - Time saved: 300 hours/year

  - Value of time: $50/hour

  - Annual benefit = 300 × 50 = $15,000

If the tool lasts 3 years:

- Total benefit = (15\*3) = $45,000
- Total cost = $20,000 + (3 × $2,000) = $26,000
- Net Benefit = $19,000 → Project is worthwhile

## ⚠️ Limitations of CBA

- Intangible benefits (like user satisfaction) are hard to quantify
- May oversimplify complex projects
- Accuracy depends on estimation reliability

---

---

---

# Information modeling / Data Modeling

Data modeling is the process of creating a **visual representation of a system’s data** — including how data is stored, organized, and related to other data. It’s like designing a blueprint for how your data will be handled in a database or application.

![alt text](image-25.png)

## Types of Data Models

| Type                 | Description                                                                                   | Example Tools          |
| -------------------- | --------------------------------------------------------------------------------------------- | ---------------------- |
| **Conceptual Model** | High-level; shows business entities and relationships                                         | ER diagrams            |
| **Logical Model**    | More detailed; includes attributes, keys, and data types (without focusing on implementation) | UML, ER tools          |
| **Physical Model**   | Implementation-specific; includes tables, columns, indexes, data types for a DBMS             | SQL scripts, DB schema |

---

![alt text](image-27.png)

## Basic Elements in Data Modeling

| Element          | Description                                                     |
| ---------------- | --------------------------------------------------------------- |
| **Entity**       | A real-world object or concept (e.g., User, Product)            |
| **Attribute**    | A property of an entity (e.g., name, email)                     |
| **Relationship** | How two entities are connected (e.g., a User _places_ an Order) |
| **Primary Key**  | Uniquely identifies each record in a table                      |
| **Foreign Key**  | Connects records between related tables                         |

## Common Data Modeling Techniques

| Technique                             | Description                                                                                                                              | Use Case                                          |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| **Entity-Relationship (ER) Modeling** | Uses entities, attributes, and relationships to describe data. Often visualized with ER diagrams.                                        | Traditional databases, relational database design |
| **Relational Modeling**               | Focuses on organizing data into tables (relations), with rows and columns. Uses keys and constraints.                                    | SQL-based RDBMS like MySQL, PostgreSQL            |
| **Hierarchical Modeling**             | Data is organized in a tree-like structure, with parent-child relationships.                                                             | XML data, legacy systems (IBM IMS)                |
| **Network Modeling**                  | Like hierarchical but more flexible — entities (nodes) can have multiple relationships (graph-like).                                     | Legacy databases, network databases               |
| **Object-Oriented Modeling (OOM)**    | Models data as objects with attributes and methods. Useful when designing databases for OOP applications. ULM It is a tool for doing OOM | Used in OOP systems (Java, C++, Python)           |

![alt text](image-28.png)

## Hierarchical Modeling

> Page: 96

## Network Modeling

> Page: 96

## Relational Modeling

> Page: 97

![alt text](image-29.png)

## Object-Oriented Data Modeling (OODM)

Object-Oriented Data Modeling (OODM) is a way of designing a database or system where **data is modeled as objects**, similar to how it is represented in object-oriented programming (OOP).

It combines **data (attributes) and behavior (methods) into objects**, which makes it intuitive for developers who work with OOP languages like Java, Python, or C++.

## Relational vs Object-Oriented Modeling

| Feature                | Relational Model                   | Object-Oriented Model           |
| ---------------------- | ---------------------------------- | ------------------------------- |
| Data is represented as | Tables (rows & columns)            | Objects (instances of classes)  |
| Relationships          | Foreign keys, joins                | References (object pointers)    |
| Behavior (methods)     | Not supported                      | Supported inside objects        |
| Inheritance            | Not directly supported             | Fully supported                 |
| Ideal for              | Structured data, SQL-based systems | OOP-based systems, complex data |

## Core Concepts of OODM

| Concept           | Description                                              |
| ----------------- | -------------------------------------------------------- |
| **Class**         | A blueprint for objects (defines attributes and methods) |
| **Object**        | A real-world entity (instance of a class)                |
| **Attribute**     | A property of a class/object (like a column in a table)  |
| **Method**        | A function/behavior defined in the class                 |
| **Encapsulation** | Data and behavior are bundled together                   |
| **Inheritance**   | One class can inherit properties/methods from another    |

> ![alt text](image-30.png)
> The Student, Doctor, and Engineer classes are inheriting from the Person class

> boxes represent classes, not objects.

### In OODM, we often use UML Class Diagrams to represent:

- Classes with attributes and methods

- Relationships: associations, inheritance, aggregation, composition

## Used In:

- Object-Oriented DBMS (e.g., db4o, ObjectDB)
- ORM frameworks (e.g., Hibernate(java), Sequelize, Prisma(js/ts))
- UML-based design tools
- Software systems built with OOP languages

## Entity-Relationship Model

The Entity-Relationship (ER) Model is a conceptual framework used to describe the structure of a database. It helps in database design by identifying `entities` (things), `attributes` (properties), and `relationships` (connections).

**The ER Diagram (ERD) is the visual representation of the ER Model**. It uses symbols like rectangles, diamonds, and ellipses to show how data is organized and related.

![alt text](image-31.png)

| Concept                   | Description & Symbol                            | Example                   |
| ------------------------- | ----------------------------------------------- | ------------------------- |
| **Entity**                | Real-world object (🔲 Rectangle)                | `Student`, `Course`       |
| **Attribute**             | Property of entity (⚪ Ellipse)                 | `Name`, `RollNo`, `Title` |
| **Primary Key**           | Unique identifier (Underlined)                  | `RollNo`, `CourseID`      |
| **Relationship**          | Association (🔷 Diamond)                        | `Enrolled`, `Teaches`     |
| **Weak Entity**           | Depends on another (Double Rectangle)           | `Dependent` of `Employee` |
| **Multivalued Attribute** | Has multiple values (Double Ellipse)            | `PhoneNumbers`            |
| **Derived Attribute**     | Computed from other attributes (Dashed Ellipse) | `Age` from `DOB`          |

### Relationship Types (Cardinality)

| Type                | Example                                                        |
| ------------------- | -------------------------------------------------------------- |
| One-to-One (1:1)    | A person has one passport                                      |
| One-to-Many (1\:N)  | One teacher teaches many students                              |
| Many-to-Many (M\:N) | Students enroll in many courses, each course has many students |

![alt text](image-33.png)

<br>

---

<br>
<br>
<br>
<br>

# <center> SRS Docs </center>

### [Video](https://www.youtube.com/watch?v=Os5j6xGVGVU)

An SRS (Software Requirements Specification) is a formal document that describes:

- What the software will do.
- How it will perform.
- The constraints under which it must operate.

It acts as a **contract** between the customer (or client) and the development team. It ensures that all stakeholders have a common understanding of the system.

It is developed during the Requirements Engineering phase of the Software Development Life Cycle (SDLC), and is crucial for ensuring a successful software project.

## Purpose of SRS

The main goals of an SRS are:

- To provide a clear, complete, and unambiguous description of what the software will do.
- To serve as a foundation for design, development, testing, and maintenance.
- To act as a binding agreement between clients and developers.
- To reduce chances of miscommunication and rework later in the project.

## Characteristics of a Good SRS

A well-written SRS must be:

| Characteristic  | Explanation                                                        |
| --------------- | ------------------------------------------------------------------ |
| **Correct**     | Should accurately reflect all real requirements.                   |
| **Unambiguous** | No vague terms like “fast”, “easy to use” etc.                     |
| **Complete**    | All major requirements should be listed.                           |
| **Consistent**  | No conflicting or contradictory requirements.                      |
| **Verifiable**  | Each requirement must be testable.                                 |
| **Modifiable**  | Easy to change as the system evolves.                              |
| **Traceable**   | Each requirement should link back to business goals or user needs. |

---

# Main Components of an SRS Document - imp

The **IEEE 830** standard is the most commonly followed **structure** for documenting sys re
quirements. Major components include:

## 1. Introduction

### 1.1 Purpose

- Why the SRS document is being written.
- Who the intended audience is.

### 1.2 Scope

- What the software product will do.
- The major features and functionalities.
- What is in-scope and out-of-scope.

### 1.3 Definitions, Acronyms, Abbreviations

- Explanation of terms used in the document.

### 1.4 References

- List of external documents referred to, like IEEE standards, user manuals, etc.

### 1.5 Overview

- A brief guide to what the rest of the SRS contains.

## 2. Overall Description

### 2.1 Product Perspective

- Where the system fits in a larger system (if any).
- Whether it’s standalone or part of another system.

### 2.2 Product Functions

- A summary of major features.
- Can be supported by block diagrams or use-case diagrams.

### 2.3 Operating Environment

- Hardware, software, network environments where the system will run.

### 2.4 Design and Implementation Constraints

- Programming language, database, hardware limits, etc.

### 2.5 Assumptions and Dependencies

- External factors that affect system requirements.

## 3. Specific Requirements

This is the most detailed section.

### 3.1 Functional Requirements

- Describes the functionality of the system.
- Each function is detailed as an input → process → output.

Example:

- The system shall allow users to upload PDF files.
- The system shall extract text from uploaded PDF documents.

### 3.2 Non-Functional Requirements

Includes:

- Performance: Response time, speed.
- Security: Authentication, data privacy.
- Usability: UI/UX expectations.
- Reliability: Uptime, fault tolerance.
- Maintainability, Scalability, etc.

### 3.3 External Interface Requirements

a) User Interface
Layout, navigation, accessibility

b) Hardware Interface
If any hardware is involved (e.g., printers, sensors)

c) Software Interface
Interaction with OS, databases, third-party APIs

## 4. Appendices (Optional)

- Glossary
- Legal constraints
- Future scope

## 5. Index (Optional)

For navigation in long documents

<br>
<br>
<br>

---

# EG:

<details close>
<summary>----Real Example----?</summary>
<br>

# Software Requirements Specification (SRS)

## 1. Introduction

### 1.1 Purpose

The purpose of this document is to define the software requirements for the "Chat with PDF" web application. The system enables users to upload PDF documents and engage in a conversational interface to query and extract information from the contents of the document. The application is designed for students, researchers, and professionals who need to efficiently interact with and understand large PDFs.

### 1.2 Scope

The system allows users to:

- Upload PDF files.
- Extract and index content from PDFs using LangChain and vector embeddings.
- Query the PDF in natural language.
- Receive accurate, context-aware answers based on the document content.
  The system is built using the **MERN stack** (MongoDB, Express.js, React, Node.js) and leverages **LangChain**, **OpenAI APIs**, and **vector databases** (e.g., Pinecone, Chroma, or similar).

### 1.3 Definitions, Acronyms, and Abbreviations

- **PDF**: Portable Document Format
- **MERN**: MongoDB, Express.js, React, Node.js
- **API**: Application Programming Interface
- **LLM**: Large Language Model
- **RAG**: Retrieval-Augmented Generation
- **SRS**: Software Requirements Specification

### 1.4 References

- IEEE Std 830-1998: IEEE Recommended Practice for Software Requirements Specifications
- LangChain Documentation: https://docs.langchain.com/
- OpenAI API Documentation: https://platform.openai.com/docs

## 2. Overall Description

### 2.1 Product Perspective

This is a standalone web application that integrates with third-party APIs (e.g., OpenAI) and optionally connects to external vector databases for storing document embeddings.

### 2.2 Product Functions

- User authentication (optional).
- PDF upload and storage.
- Content extraction and text chunking.
- Text embedding and vector storage.
- Semantic search based on user queries.
- LLM-based answer generation.

### 2.3 User Classes and Characteristics

- **Guest Users**: Can test the app with demo files.
- **Registered Users**: Can upload, store, and chat with personal PDFs.
- **Admin**: Has access to analytics and user management.

### 2.4 Operating Environment

- Frontend: React.js
- Backend: Node.js with Express
- Database: MongoDB (for user and file metadata)
- Vector DB: Pinecone, Chroma, or a local embedding store
- LLM: OpenAI’s GPT models via API
- Hosting: Cloud-based deployment (e.g., Vercel + Render/Heroku)

### 2.5 Design and Implementation Constraints

- Limited by the API quota and latency of LLM providers.
- Maximum file size limit for PDF uploads.
- Embedding models used should support chunked input text.

## 3. Specific Requirements

### 3.1 Functional Requirements

#### 3.1.1 User Authentication

- The system shall allow users to register and log in using email/password or OAuth.
- The system shall protect user data using JWT authentication.

#### 3.1.2 PDF Upload and Storage

- The system shall allow authenticated users to upload PDF files.
- The system shall store metadata (filename, user ID, upload date).

#### 3.1.3 PDF Parsing and Chunking

- The system shall extract text from the uploaded PDF.
- The system shall split the text into manageable chunks for embedding.

#### 3.1.4 Embedding and Storage

- The system shall convert chunks into vector embeddings using an embedding model (e.g., OpenAI embeddings).
- The system shall store vectors in a vector database associated with the document.

#### 3.1.5 Chat Interface

- The system shall allow users to enter natural language queries.
- The system shall retrieve relevant text chunks via semantic search.
- The system shall generate answers using a connected LLM with RAG (Retrieval-Augmented Generation).

#### 3.1.6 File and Session Management

- The system shall list previously uploaded PDFs for logged-in users.
- The system shall maintain a history of user interactions for each file.

### 3.2 Non-Functional Requirements

- **Performance**: Responses should be returned within 2–5 seconds for average queries.
- **Scalability**: The system should support horizontal scaling for increased load.
- **Security**: User data and documents must be encrypted at rest and in transit.
- **Usability**: The UI must be responsive and accessible on mobile and desktop devices.
- **Reliability**: The system should handle unexpected API failures gracefully with retries and fallbacks.

## 4. External Interface Requirements

### 4.1 User Interfaces

- **Login/Register Page**
- **Dashboard** (list uploaded PDFs)
- **Upload PDF Modal/Form**
- **Chat Interface** (chat bubble layout)
- **Admin Panel** (optional)

### 4.2 API Interfaces

- **OpenAI API**: For embedding and chat responses
- **LangChain Interface**: For managing the RAG pipeline
- **MongoDB Atlas**: For metadata storage
- **Vector DB API**: For embedding retrieval

### 4.3 Hardware Interfaces

- None required beyond standard web browser and internet connection.

### 4.4 Software Interfaces

- Browser: Chrome, Firefox, Edge (latest versions)
- Operating System: Platform-independent

## 5. Future Enhancements

- Multi-language PDF support.
- Support for image-based PDFs using OCR.
- Collaboration features (e.g., shared documents and annotations).
- Integration with cloud storage (Google Drive, Dropbox).

</details>

---

<br>
<br>
<br>

![alt text](image-34.png)

<br>
<br>
<br>

---

# <Center> S/W Quality Assurance </center>

[Video](https://www.youtube.com/watch?v=LNSG-yssisA&list=PLmXKhU9FNesTrw7n8ouPsSLEcduRlENHr&index=15)

[Read Thru](https://medium.com/@suraif16/software-quality-assurance-101-b3fb57e47ad3 )

Software Quality Assurance (SQA) is the process of ensuring that a software product meets specific quality standards and user expectations throughout the development lifecycle.. 

SQA is applied throughout the Software Development Life Cycle (SDLC), not just during testing..

## Terms: 

- **Defect vs Bug:**
 "defect" is generally a broader term encompassing any deviation from the expected behavior or requirements of the software, while "bug" specifically refers to an error in the code causing unexpected results. 

- **Verification vs Validation**:
`verification` ensures that the software is built correctly according to specifications,
`"Are we building the product right?"`
 while `validation` ensures that the software meets the intended user needs and fulfills its intended purpose. `"Are we building the right product?"`


##  Objectives of SQA

- Ensure software quality from the beginning to end of the SDLC.

- Detect and correct errors as early as possible in the SDLC.

- Improve development processes.

- Ensure customer satisfaction.

## SQA Activities

| Activity                            | Description                                                      |
| ----------------------------------- | ---------------------------------------------------------------- |
| **Quality Planning**                | Define quality objectives, metrics, tools, responsibilities.     |
| **Process Definition**              | Establish formal processes based on models like ISO, CMMI.       |
| **Formal Technical Reviews (FTR)**  | Structured reviews to identify defects early.               |
| **Testing**                         | Unit, Integration, System, Acceptance testing to detect defects. |
| **Metrics Collection and Analysis** | Use data to assess quality and suggest improvements.             |
| **Risk Management**                 | Identify, analyze, and mitigate software risks.                  |


##  Components of an SQA Plan (IEEE 730 Standard)

An SQA Plan defines the strategies, responsibilities, and resources needed to ensure quality. Major components include:

- **Objectives & Scope** – What the plan is for and which parts of the software it covers.

- **Roles & Responsibilities** – Who is responsible for quality assurance activities (QA team, developers, managers).
- **Quality Tasks & Methods** – What QA tasks will be done and how (like reviews, testing, audits, tools used).
- **Issue Tracking &Fixing** – How defects will be reported, tracked, and resolved.
- **Training & Standards** – What standards to follow (e.g., ISO, IEEE) and any training needed for the team.

## SQA vs Software Testing

| Feature      | SQA                          | Software Testing                      |
| ------------ | ---------------------------- | ------------------------------------- |
| Scope        | Broader, covers full SDLC    | Narrower, mostly coding & post-coding |
| Objective    | Prevent defects              | Find defects                          |
| Type         | Process-oriented             | Product-oriented                      |
| Performed by | QA team                      | Testing team                          |
| Timing       | Ongoing                      | After implementation                  |
| Example      | Process audits, code reviews | Unit, integration, system testing     |

## Standards in SQA

Some commonly followed standards:

- ISO 9001 – General quality management
- IEEE 730 – SQA plans
- CMMI (Capability Maturity Model Integration) – Process improvement model

<br>
<br>

 #  ISO 9000 Models

>page:127

<br>
<br>

---
# Capability Maturity Model*

>page:130


