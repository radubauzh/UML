# Overview

1. UML definition
2. Why UML?
3. UML Overview
4. Structure Diagrams
- Class Diagram
- Package Diagram
- Collaboration Diagram
- Deployment Diagram
- Component Diagram

5. Dynamic Diagrams
- Use Case Diagram
- Activity Diagram
- Sequence Diagram
- State Diagram

## UML definition
Unified Modeling Language, UML is not a method or process but the Univied Development is.

## Why UML?
- Reduces risks by documenting assumptions
  - domain models, requirements, architecture, design, implementation, ... 
- Represents industry standard
  -	more tool support, more people understand your diagrams, less education needed 
-	Is reasonably well-defined although there are interpretations and dialects 
-	Is open -> stereotypes, tags and constraints to extend basic -> constructs has a meta-meta-model for advanced extensions 


## UML Overview

![Image](overview.png)

# Structure Diagrams
Structure diagrams show the static structure of the system and its parts on different abstraction and implementation levels and how they are related to each other. The elements in a structure diagram represent the meaningful concepts of a system, and may include abstract, real world and implementation concepts.!


## Class Diagram
Represents the static structure of the system in terms of classes and their relations. 
Shows static structure of the designed system, subsystem or component as related classes and interfaces, with their features like their attributes, operations (or methods), constraints and relationships - associations, generalizations, dependencies, etc. They detail how types are defined and structurally related.

![Image](class.png)

**Pros**
- Useful to represent how types are defined and related 
- They are useful to capture the essence of one or more design decisions 

**Cons**
- Poor vehicle for capturing any run- time property of the code 

## Package Diagram
Shows packages and relationships between the packages. Also shows Structure and dependencies between sub-systems or modules. Is used to simplify complex class diagrams, you can group classes into packages. A package is a collection of logically related UML elements.

![Image](package.png)

## Collaboration Diagram
Is a spatial representation of objects, relations, and interactions. 
The collaboration diagram is used to show the relationship between the objects in a system. Shows scenarios as flows of messages between objects. Both, sequence and collaboration diagrams represent the same information but differently. 

![Image](collaboration.png)

## Deployment Diagram
Represents the deployment of a system on hardware. 
The deployment diagram visualizes the physical hardware on which the software will be deployed. It portrays the static deployment view of a system. It involves the nodes and their relationships. It ascertains how software is deployed on the hardware. It maps the software architecture created in design to the physical system architecture, where the software will be executed as a node. Since it involves many nodes, the relationship is shown by utilizing communication paths.

![Image](deployment.png)

## Object Diagram
Represents objects and their relations; corresponds to simplified collaboration diagrams (no message sends). 
Object diagrams show particular instantiations of systems and their behavior”. A UML object diagram represents a specific instance of a class diagram at a certain moment in time. When represented visually, you'll see many similarities to the class diagram. An object diagram focuses on the attributes of a set of objects and how those objects relate to each other.

![Image](object.png)

## Component Diagram
Represents the physical components of a system. 
A component diagram breaks down the actual system under development into various high levels of functionality. Each component is responsible for one clear aim within the entire system and only interacts with other essential elements on a need-to-know basis.

![Image](component.png)

# Behavior Diagrams
Behavior diagrams show the dynamic behavior of the objects in a system, which can be described as a series of changes to the system over time.

## Use Case Diagram
Represents the functionality of the system from the point of the user of that system. 
A use case is a generic description of an entire transaction involving several actors. A use case diagram presents a set of use cases (ellipses) and the external actors that interact with the system. Dependencies and associations between use cases may be indicated. A use case is a snapshot of one aspect of your system. The sum of all use cases is the external picture of your system. As use cases appear, assess their impact on the domain model. A domain model in software engineering is a conceptual model of all the topics related to a specific problem. Use cases can drive domain modeling by highlighting the key concepts 

![Image](usecase.png)

## Activity Diagram
Represents the behavior of one operation in terms of actions. 
An activity diagram models the control flow (i.e., execution states) of a computation or Workflow (within the system rather than the implementation). In other words: an object-oriented flowchart. Activity diagrams can express collaboration. Swimlanes group activities by responsibilities. Object flows depict objects that are the outputs or inputs of activities 

![Image](activity.png)

## Sequence Diagram
Is a temporal representation of objects and their interaction. 
A sequence diagram depicts a scenario by showing the interactions among a set of objects in Temporal order. Objects (not classes!) are shown as vertical bars. Events or message dispatches are shown as horizontal (oder DE: schräg) arrows from the sender to the receiver. Message flow is represented by a vertical dotted line that extends across the bottom of the page.

![Image](sequence.png)

## State Diagram
Represents the behaviour of a class in terms of (evolution of) its state. 
The state machine diagram is also called the Statechart or State Transition diagram, which shows the order of states underwent by an object within the system. It captures the software system's behavior. It models the behavior of a class, a subsystem, a package, and a complete system.
It tends out to be an efficient way of modeling the interactions and collaborations in the external entities and the system. It models event-based systems to handle the state of an object. It also defines several distinct states of a component within the system. Each object/component has a specific state.
Following are the types of a state machine diagram that are given below:

**1.	Behavioral state machine**
The behavioral state machine diagram records the behavior of an object within the system. It depicts an implementation of a particular entity. It models the behavior of the system.
**2.	Protocol state machine**
It captures the behavior of the protocol. The protocol state machine depicts the change in the state of the protocol and parallel changes within the system. But it does not portray the implementation of a particular component.


![Image](state.png)



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/radubauzh/UML/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
