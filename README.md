# Pillur: A Platform for Robotic Software Development with Catalyst

## Overview

Pillur is an innovative platform designed to revolutionize robotic software development by applying the principles of Constructor Theory. Rooted in the pioneering ideas of David Deutsch and Chiara Marletto, Pillur aims to redefine how robotic software is conceptualized, developed, and tested. At its core, Pillur integrates **Catalyst**, a task-oriented Domain Specific Language (DSL) that allows developers to define robotic tasks in terms of "CAN" and "CAN'T" constraints.

## Why Pillur?

The current landscape of robotic software development is heavily influenced by probabilistic models and methodologies. While effective in some contexts, these approaches often lack the precision and reliability needed in robotics. **Pillur** challenges this paradigm by introducing a counterfactual approach, where tasks are defined by what is possible and impossible, rather than by probabilities. This shift enhances the accuracy of robotic software and opens up new avenues for innovation.

### Key Concepts

- **Constructor Theory:** The foundation of Pillur, Constructor Theory shifts the focus from traditional laws of motion to principles that define what tasks are possible or impossible. In the context of robotics, this means creating software that can perform tasks reliably and deterministically.

- **Catalyst Language:** Catalyst is a minimalistic DSL within Pillur that allows developers to specify tasks for robots using "CAN" and "CAN'T" declarations. This language is designed to manage and execute tasks based on the principles of Constructor Theory, ensuring that robotic systems adhere to the defined constraints.

- **Counterfactuals in Robotics:** Pillur’s approach is rooted in counterfactual reasoning—defining tasks based on outcomes that can or cannot occur. This leads to more precise and reliable software, reducing the complexity and unpredictability associated with traditional approaches.

- **Deterministic Software Development:** By eliminating probabilistic elements, Pillur ensures that robotic software behaves predictably and consistently, even in complex environments.

### Example Workflow with Catalyst

Consider the following task definition written in Catalyst's TDL (Task Definition Language):

```yaml
task: PickAndPlaceBlock
description: Move the block to the target area without hitting obstacles.
actions:
  - CAN: move(arm, block_location)
  - CAN: grasp(arm, block)
  - CAN: move(arm, target_location)
  - CAN'T: collide(arm, obstacles)
```
# Reference

1. **[Title of the Reference]**  
   Author(s): [Author Name(s)]  
   Link: [URL]

2. **[Title of the Reference]**  
   Author(s): [Author Name(s)]  
   Link: [URL]

3. **[Title of the Reference]**  
   Author(s): [Author Name(s)]  
   Link: [URL]
---

# Pillur: Applying Constructor Theory to Robotic Software Development

## Overview

**Pillur** is an innovative project focused on revolutionizing robotic software development by applying the principles of Constructor Theory. Rooted in the groundbreaking ideas of David Deutsch and Chiara Marletto, Pillur aims to redefine how robotic software is conceptualized, developed, and tested. By leveraging Constructor Theory, Pillur seeks to eliminate probabilistic methodologies from software development, offering a deterministic and counterfactual approach that simplifies complex tasks in robotics.

## Why Pillur?

The current landscape of robotic software development is heavily influenced by probabilistic models and methodologies. These approaches, while effective in certain contexts, often fall short in providing the precision and reliability required in robotics. Pillur challenges this paradigm by introducing a counterfactual approach, where tasks are defined by what is possible and impossible, rather than by probabilities. This shift not only enhances the accuracy of robotic software but also opens up new possibilities for innovation in the field.

## Why Catalyst?

Catalyst, as a task-oriented robotic software language, would focus on leveraging the possibilities and constraints (CAN and CAN'T) of tasks in robotic systems. It provides a structured way to define, manage, and execute tasks based on the principles of Constructor Theory, where tasks are seen as transformations governed by the laws of physics.
Counterfactual API which conists of Can and Cant declarations that compose a robotic system.

About the power of taking counterfactual explanations of the world seriously.

Counterfactual explanations of the world are explanations about what physical events could or could not be made to happen.

## Key Concepts

- **Constructor Theory**: The foundation of Pillur, Constructor Theory shifts the focus from traditional laws of motion to principles that define what tasks are possible or impossible. In the context of robotics, this means creating software that can perform tasks reliably and deterministically.
  
- **Counterfactuals in Robotics**: Pillur’s approach to robotic software development is rooted in counterfactual reasoning—defining tasks based on the outcomes that can or cannot occur. This allows for more precise and reliable software, reducing the complexity and unpredictability of traditional approaches.
  
- **Deterministic Software Development**: By eliminating probabilistic elements from the development process, Pillur ensures that robotic software behaves predictably and consistently, even in complex environments.

## Project Goals

- **Redefine Robotic Software Development**: Apply Constructor Theory to create a new framework for developing robotic software, focusing on deterministic and counterfactual principles.
  
- **Create a Task-Oriented Language**: Develop a programming language within Pillur that allows developers to express and manage tasks in terms of what is possible and impossible, enhancing the reliability and precision of robotic applications.
  
- **Develop and Test Robotic Applications**: Use Pillur’s framework to build and test robotic applications that demonstrate the practical benefits of a Constructor Theory-based approach.

## Integration of the C4 Model

To ensure the scalability and clarity of Pillur, the C4 Model is applied, breaking down the system into four distinct levels of abstraction: Context, Containers, Components, and Code. This model facilitates a structured and detailed understanding of the system, aiding both development and communication.

### Level 1: Context

At the Context level, Pillur is viewed in relation to the broader ecosystem of robotic software development. Here, Pillur is identified as the central system that interacts with users (robotic software developers), external systems like cloud platforms and ROS, and databases for storing tasks and system states.

### Level 2: Containers

The Containers level delves deeper, identifying key components such as the Task Management API, Task Orchestrator, ROS Integration Layer, Database, and User Interface. Each container serves a specific role in the overall architecture, with clear interactions and responsibilities defined.

### Level 3: Components

Components within each container are further broken down, showing how they collaborate to fulfill their roles. For example, the Task Management API contains services for task definition, execution, and monitoring, while the Task Orchestrator includes a scheduler, execution controller, and error handler.

### Level 4: Code

At the Code level, specific classes, methods, and functions within each component are detailed, providing insight into the implementation of Pillur's architecture. This level is essential for developers working directly on the codebase, particularly in highly regulated environments.

## Vision

Pillur envisions a future where robotic software development is streamlined through the application of Constructor Theory and the structured approach provided by the C4 Model. This combination ensures that Pillur is not only powerful and flexible but also clear and understandable to all stakeholders. By focusing on tasks as the fundamental units of work and leveraging the principles of Constructor Theory, Pillur provides developers with the tools they need to create more robust, scalable, and flexible robotic applications.

## Getting Started

1. **Clone the Repository**:  
   `git clone https://github.com/yourusername/Pillur.git`
  
2. **Explore the Examples**:  
   Start by exploring the task-oriented language examples and C4 Model diagrams provided in the repository.

3. **Contribute**:  
   We welcome contributions from developers, researchers, and robotics enthusiasts. Help us shape the future of robotic software development by contributing to Pillur.

## License

Pillur is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.




# Pillur: Applying Constructor Theory to Robotic Software Development

## Overview

**Pillur** is an innovative project focused on revolutionizing robotic software development by applying the principles of constructor theory. Rooted in the groundbreaking ideas of David Deutsch and Chiara Marletto, Pillur aims to redefine how robotic software is conceptualized, developed, and tested. By leveraging constructor theory, Pillur seeks to eliminate probabilistic methodologies from software development, offering a deterministic and counterfactual approach that simplifies complex tasks in robotics.

## Why Pillur?

The current landscape of robotic software development is heavily influenced by probabilistic models and methodologies. These approaches, while effective in certain contexts, often fall short in providing the precision and reliability required in robotics. Pillur challenges this paradigm by introducing a counterfactual approach, where tasks are defined by what is possible and impossible, rather than by probabilities. This shift not only enhances the accuracy of robotic software but also opens up new possibilities for innovation in the field.

## Key Concepts

- **Constructor Theory**: The foundation of Pillur, constructor theory shifts the focus from traditional laws of motion to principles that define what tasks are possible or impossible. In the context of robotics, this means creating software that can perform tasks reliably and deterministically.
  
- **Counterfactuals in Robotics**: Pillur’s approach to robotic software development is rooted in counterfactual reasoning—defining tasks based on the outcomes that can or cannot occur. This allows for more precise and reliable software, reducing the complexity and unpredictability of traditional approaches.
  
- **Deterministic Software Development**: By eliminating probabilistic elements from the development process, Pillur ensures that robotic software behaves predictably and consistently, even in complex environments.

## Project Goals

1. **Redefine Robotic Software Development**: Apply constructor theory to create a new framework for developing robotic software, focusing on deterministic and counterfactual principles.
  
2. **Create a Task-Oriented Language**: Develop a programming language within Pillur that allows developers to express and manage tasks in terms of what is possible and impossible, enhancing the reliability and precision of robotic applications.
  
3. **Develop and Test Robotic Applications**: Use Pillur’s framework to build and test robotic applications that demonstrate the practical benefits of a constructor theory-based approach.

## External Links
  - https://www.constructortheory.org/
  - https://www.daviddeutsch.org.uk/
  - https://www.chiaramarletto.com/
  - https://www.chiaramarletto.com/books/the-science-of-can-and-cant/
  - https://www.thebeginningofinfinity.com/
## Planned Repository Structure

```plaintext
Pillur/
│
├── .github/workflows/
│   └── ci-cd.yml               # Continuous integration and deployment workflows for Pillur.
│
├── Constructor_Theory/
│   └── Theory.md               # Detailed explanation of how constructor theory is applied in Pillur.
│
├── Robotics/
│   └── Robotics_Applications/  # Directory containing sample robotic applications developed using Pillur.
│
├── Language/
│   └── Task_Language.md        # Documentation on the task-oriented language being developed.
│
├── Tests/
│   └── Test_Framework.md       # Framework and guidelines for testing robotic applications within Pillur.
│
├── Examples/
│   └── Basic_Robot.md          # Examples and tutorials demonstrating how to use Pillur.
│
├── README.md                   # Project overview and getting started guide.
└── LICENSE                     # Licensing information.
