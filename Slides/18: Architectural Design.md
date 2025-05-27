### Chapter 18: Architectural Design

#### Slide 1: What is Software Architecture?

* Represents the structure of data and program components.
* Considers architectural style, component structure, properties, and interrelationships.
* Identifies structural elements, interfaces, and component behavior.
* Enables design analysis, alternative consideration, and risk reduction.
* Components can be modules, classes, databases, or middleware.

#### Slide 2: Why is Architecture Important?

* **Communication:** Facilitates dialogue among stakeholders.
* **Early Decisions:** Highlights impactful design choices.
* **System Model:** Provides a concise view of component structure and interaction.
* **Transferability:** Styles and patterns can be reused.
* **Quality:** Critical for product success and system quality.

#### Slide 3: Architectural Descriptions (AD)

* A set of work products reflecting different system views based on stakeholder concerns.
* **Metaphors:**
    * **Blueprint:** For developers, explicit information transfer.
    * **Language:** For managers/marketing, facilitates communication and negotiation.
    * **Decision:** For project managers, impacts resource allocation and tasks.
    * **Literature:** For reuse and knowledge transfer to maintenance staff.

#### Slide 4: Architectural Decisions

* System architects decide on features to meet concerns.
* Decisions themselves offer insight into system structure.
* Documenting decisions provides rationale and historical record.
* Lightweight Architectural Decision Record (ADRs) for agile development: title, context, decision, status, consequences.
* Explicitly defining architecture and documenting choices is crucial.

#### Slide 5: Agility and Architecture

* Important for complex systems despite "big design upfront" concerns.
* Integrate architectural practices into agile models.
* Use architectural prototypes (walking skeletons) and explicit work products.
* **Storyboarding:** Architects prioritize architectural user stories in sprints.


## Notes

**1. What is Architectural Design?**
* Architectural design represents the structure of data and program components necessary to build a computer-based system.
* It encompasses the architectural style, the structure and properties of system components, and their interrelationships.
* Software architecture identifies a system's "structural elements and their interfaces," along with the "behavior" of individual components and subsystems.
* It is a representation that enables analysis of design effectiveness against requirements, consideration of alternatives, and reduction of construction risks.
* A software component in architectural design can range from a program module or object-oriented class to databases and "middleware".
* Component properties are characteristics needed to understand how components interact, while internal properties (e.g., algorithm details) are not specified at this level.
* Relationships between components can be simple procedure calls or complex database access protocols.

**2. Why is Architecture Important?**
* It facilitates communication among all stakeholders by providing a common representation.
* It highlights early design decisions that profoundly impact subsequent software engineering work.
* It offers a relatively small model of how system components are structured and work together.
* Architectural design models and patterns are transferable, allowing application to other systems and enabling predictable architecture descriptions.
* Good architectural decisions are critical to product success, as they set the system's structure and determine its quality.

**3. Architectural Descriptions**
* An architectural description (AD) is a set of work products reflecting different views of the system, driven by various stakeholder concerns.
* **Metaphors for understanding software architecture:**
    * **Blueprint Metaphor:** Familiar to developers, it's a means of transferring explicit information from architects to designers and software engineers.
    * **Language Metaphor:** Favored by customer-focused stakeholders (managers, marketing experts), it facilitates communication across groups and forms a basis for negotiation.
    * **Decision Metaphor:** Project managers view architecture as the product of decisions involving trade-offs (cost, usability, maintainability, performance) that affect resource allocation, tasks, and team structure.
    * **Literature Metaphor:** Supports documenting past architectural solutions, transferring knowledge for maintenance, and promoting component and design reuse.

**4. Architectural Decisions**
* System architects consider alternatives and decide on features that best meet stakeholder concerns for each view of the architectural description.
* Architectural decisions themselves can be considered a view of the architecture, providing insight into system structure and conformance to concerns.
* Documenting major decisions (e.g., using a template) provides rationale and a historical record for future modifications.
* For agile developers, a lightweight architectural decision record (ADR) includes title, context, decision, status, and consequences.
* Defining architecture first and explicitly stating architectural choices is crucial, especially for innovative products. Documenting what worked helps engineers decide when to innovate versus reuse.

**5. Agility and Architecture**
* While some agile developers equate architectural design with "big design upfront" leading to unnecessary documentation, most agree it's important for complex systems.
* Integrating new architectural design practices into agile process models is important.
* Agile teams anticipate architectural elements from user stories, create architectural prototypes (walking skeletons), and develop explicit architectural work products.
  * Architects contribute and prioritize architectural user stories with business stories in sprints, ensuring high architectural quality.

### References
Pressman, Roger S., and Bruce R. Maxim. Software Engineering: A Practitioner's Approach. 9th ed., McGraw-Hill Education, 2019.


