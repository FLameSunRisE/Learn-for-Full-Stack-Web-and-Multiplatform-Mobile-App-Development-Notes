# Angular Service Basics

## The Model View Controller Framework

* Design Patterns

  * Well-documented solution to a recurring problem

* The Model-View-Controller \(MVC\) Framework

  * Define

    * Isolation of domain logic from user interface

    * Permits independent development, testing and maintenance \(separation of concerns\)

  
    ![](blob:file:///1f1cf47a-e6f1-4c87-b635-be2d089fc236)

  * Model

    * manages the behavior and data of the application domain

    * responds to requests for information about its state \(usually from the view\)

    * responds to instructions to change state \(usually from the controller\)

  * View

    * renders the model into a form suitable for interaction, typically a user interface element

    * Multiple views can exist for a single model for different purposes

    * A viewport typically has a one to one correspondence with a display surface and knows how to render to it

  * Controller

    * receives user input and initiates a response by making calls on model objects

    * A controller accepts input from the user and instructs the model and viewport to perform actions based on that input

* Model View View-Model \(MVVM\)

  * 
  ![](blob:file:///bca90ba5-bd5a-465f-92ae-47dcab653a12)  


