# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. **What does the ___word___ 'polymorphism' mean?**  
    Many forms/shapes.

2. **What does it mean when we apply polymorphism to OO design? Give a simple Java example.**  
    In OOP, polymorphism means an object can be multiple object types. For example, if a Car class inherits from a Vehicle class, a car object could be of either Car or Vehicle.

3. **What can we use to implement polymorphism in Java?**  
    Inhertitance and interfaces.

4. **How many 'forms' can an object take when using polymorphism?**  
    As many as the programmer wishes.

5. **Give an example of when you could use polymorphism.**  
    A Dealership could sell Cars and Motorbikes. The dealership could group these in a list of a common object type. Cars and Motorbikes could inherit a Vehicle superclass in which case the common dealership list could be of type Vehicle. Alternatively, the Cars and Motorbikes could share a common interface (e.g. IDrive) with the dealership list being of type IDrive.




# Composition and Aggregation

6. **What do we mean by 'composition' in reference to object-oriented programming?**  
    Composition is a relationship between objects where the child object cannot exist without the parent object.

7. **When would you use composition? Provide a simple example in Java.**  
    It would be used in OOP when the programmer does not want an object to exist independently of another. For example, a Heart class is part of the Human class. The Heart class could only exist if the Human class does, as part of the Human class.


8. **Give a difference between composition and aggregation?**  
    In aggregation, a child object can exist independently of its part object, whereas it cannot in composition.

9. **What is/are the advantage(s) of using composition/aggregation?**  
    They allow a class to use behaviours from other classes.

10. **When using composition, when an object is destroyed, what happens to all the objects it is composed of?**  
    The child objects are destroyed as they cannot exist independently.

11. **When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?**  
    The child objects still exist, they can exist independently of the parent object.
