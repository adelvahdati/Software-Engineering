## Software Testing - Component Level

### I. Introduction to Software Component Testing
* **Definition:** Software component testing involves a strategy outlining the steps, planning, execution, effort, time, and resources required for testing.
* **Tactics:** Within this strategy, component testing implements tactics for test planning, test-case design, test execution, and data collection/evaluation.
* **Purpose:** Testing aims to uncover inadvertently made errors during software design and construction.
* **Scope:** A component testing strategy considers testing individual components and their integration into a working system.
* **Importance:** Testing often consumes more project effort than other software engineering activities. Haphazard testing leads to wasted time, unnecessary effort, and undetected errors.
  * Haphazard testing means that the testing process is unplanned, unsystematic, and lacks a structured approach.
* **Process Overview:** Testing begins "in the small" (focus on a single or small group of components) and progresses "to the large" (integration into the complete system).
* **Work Product:** A test specification documents the testing approach, including an overall strategy and specific testing steps and test case types.
* **Responsibility:** Component testing is primarily the responsibility of individual software engineers. The testing approach is influenced by the software integration approach and design philosophy adopted by the development team.

### II. A Strategic Approach to Software Testing
* **Systematic Activity:** Testing is a planned and systematically conducted set of activities.
* **Generic Characteristics of Testing Strategies:**
    * Testing starts at the component level and expands outwards towards system integration.
    * Different techniques are suitable for different approaches and stages.
    * Testing is done by developers and, for large projects, an independent test group (ITG).
    * Debugging is distinct from testing but must be accommodated in any strategy.
    * A strategy includes tactics for low-level (source code verification) and high-level tests (validation against customer requirements).
    * Provides guidance for practitioners and milestones for managers.
    * Progress should be measurable, and problems should surface early due to deadline pressures.
 
### III. Verification and Validation (V&V)
* **Definition:** Software testing is a part of Verification and Validation (V&V).
* **Verification:** "Are we building the product right?" (Ensures software correctly implements a specific function).
* **Validation:** "Are we building the right product?" (Ensures software is traceable to customer requirements).
* **Scope of V&V:** Encompasses many Software Quality Assurance (SQA) activities, including Technical reviews, audits, monitoring, various testing types (development, usability, acceptance, etc.).

### IV. Organizing for Software Testing
* **Conflict of Interest:** Developers testing their own software can lead to a conflict of interest as they have a vested interest in demonstrating error-free, on-schedule, and within-budget completion.
* **Psychological Aspect:** Software development is constructive; testing is psychologically destructive to the builder's creation, potentially leading to less thorough testing aimed at demonstrating functionality rather than uncovering errors.
* **Developer's Responsibility:** Software developers are always responsible for testing individual units/components to ensure proper function and behavior. They also often conduct integration testing.
* **Independent Test Group (ITG):**
    * Becomes involved after the software architecture is complete.
    * Removes the conflict of interest inherent in self-testing.
    * ITG personnel are paid to find errors.
    * Developers and ITG work closely; developers must be available to correct errors.
    * ITG is part of the project team, involved from analysis and design, and often reports to the SQA organization for independence.
 
### V. The Big Picture of Software Testing
* **Four Sequential Steps:**
    1.  **Unit Testing:** Focuses on individual components to ensure proper function. Employs techniques to exercise specific control paths for coverage and error detection.
    2.  **Integration Testing:** Assembles components to form the complete software package, addressing verification and program construction. Uses techniques focusing on inputs/outputs, and sometimes specific program paths.
    3.  **Validation Testing:** High-order tests conducted after integration, evaluating validation criteria from requirements analysis to ensure all functional, behavioral, and performance requirements are met.
    4.  **System Testing:** Falls within broader computer system engineering. Verifies that software meshes properly with other system elements (hardware, people, databases) and that overall system function/performance is achieved.


### VI. Test-Case Design for Unit Testing
* **Design Before Code:** It's beneficial to design unit test cases before developing component code to ensure the code will pass the intended tests.
* **Unit Test Focus Areas:**
    * **Module Interface:** Test proper information flow into and out of the unit.
    * **Local Data Structures:** Examine data integrity during algorithm execution.
    * **Independent Paths:** Exercise all independent paths through the control structure to ensure all statements are executed at least once. This uncovers errors from incorrect computations, comparisons, or control flow.
    * **Boundary Conditions:** Test module operation at boundaries (e.g., array limits, loop iterations, min/max values) where software often fails.
    * **Error-Handling Paths:** Test all paths related to error handling.
 
### References
Pressman, Roger S., and Bruce R. Maxim. Software Engineering: A Practitioner's Approach. 9th ed., McGraw-Hill Education, 2019.
