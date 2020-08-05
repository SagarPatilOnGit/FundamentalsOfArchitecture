# Fundamentals Of Architecture

• An Architectural Style is the application design at the highest level of abstraction. It’s the highest level of granularity and it specifies layers, high-level modules of the application and how those modules and layers interact with each other, the relations between them. Examples of Architectural Styles:
	Component-based
	Monolithic application
	Micro Services
	Micro front Ends
	Layered
	Pipes and filters
	Event-driven
	Publish-subscribe
	Plug-ins
	Client-server
	Service-oriented

• An Architectural Pattern is a way to implement an Architectural Style. Architectural Patterns have an extensive impact on the code base, most often impacting the whole application either horizontally (i.e. how to structure the code inside a layer) or vertically (i.e. how a request is processed from the outer layers into the inner layers and back). Examples of Architectural Patterns:
	Three-tier
	Microkernel
	Model-View-Controller(MVC)
	Model-View-ViewModel(MVVM)

• A Design Pattern is a way to solve a localized problem. Design Patterns differ from Architectural Patterns in their scope, they are more localized, they have less impact on the code base, they impact a specific section of the code base, for example:
	How to instantiate an object when we only know what type needs to be instantiated at run time (maybe a Factory Class?).
	How to make an object behave differently according to its state (maybe a state machine, or a Strategy Pattern?).
  Under GoF we have Creational, Structural and Behavioural design patterns
  
Misc: Apart from above architectural / design patterns, below are few demanding architectures:
   Clean / Onion Architecture
   Serverless Architecture
