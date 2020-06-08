## MONDAY, JUNE 8th

__KNOWLEDGE GAINED:__
* learned about inheritance, interfaces, enum, abstract/final classes and
* 
* 1) inheritance:
* inheritance is a concept that defines a template class and allows other classes to inherit its attributes and methods
* for example: 
* the class "Animal" has race, numberOfLegs and casing (meaning either skin, scales, feathers, fur, etc as the beings outer shell)
* the class also has a method "makeSound()" which is set as "abstract" and has no method body; this is because the method must be available to all inherited animal classes (dog, cat, worm, fish, etc)
* but we do not know what exactly the content of "makeSound()" will be
*
* then there is a method named "eat()" which is not set as abstract because we assume that all animals feed in one way or another
* thus the method is allowed to have a body with instructions which is the same for all animals that use it
* or i can be altered if needed
*
* the class "Cat" inherits from "Animal" to which we add an attribute (liveCount), a method named "die()", and additionally an "AlreadyDeadException".
*
* 2.) interfaces:
* 
