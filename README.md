
# Animal Classification System
## Written By Courage Nduka(B)
This project implements a simple animal classification system using Object-Oriented Programming (OOP) principles in JavaScript. The system defines several classes representing different types of animals, each extending a base Animal class. These classes encapsulate specific properties and behaviors unique to their respective animal types.

## Object-Oriented Principles Used:
1. ### Inheritance:
The project demonstrates the principle of inheritance by creating subclasses for specific animal types that inherit common properties and behaviors from the base Animal class.
Example: Arthropod, Fish, Amphibia, Reptiles, AVES, and Mammal classes.

2. ### Encapsulation:
The use of classes and class methods encapsulates related properties and behaviors within each class, providing a clear and organized structure.
Example: The Animal class encapsulates common properties (name, backbone, habitant, species, characteristics) and methods (move, reproduce).

3. ### Polymorphism:
Polymorphism is demonstrated by the overridden move and reproduce methods in each subclass, where specific implementations are provided based on the type of animal.
Example: The move and reproduce methods in subclasses (Arthropod, Fish, Amphibia, Reptiles, AVES, Mammal) override the generic methods from the base Animal class.

4. ### Abstraction:
The project abstracts common properties and behaviors into the base Animal class, allowing for the creation of instances representing various animals with shared attributes and methods.
Example: The base Animal class abstracts properties and methods common to all animals.

## Classes and Their Usage:

1. ### Animal Class:
Base class for all animals.
Defines common properties and methods shared by all animals.

2. ### Arthropod Class:
Subclass for arthropods.
Introduces specific properties like numberOfLeg and methods like fly for arthropods.

3. ### Fish Class:
Subclass for fish.
Introduces specific properties like waterType and methods like oxygen for fish.

4. ### Amphibia Class:
Subclass for amphibians.
Introduces specific properties like coldBlooded and methods like hibernate for amphibians.

5. ### Reptiles Class:
Subclass for reptiles.
Introduces specific properties like hasScales and methods like lifeSpan for reptiles.

6.  ### AVES Class:
Subclass for birds (AVES).
Introduces specific properties like wings and methods like hunters for birds.

7. ### Mammal Class:
Subclass for mammals.
Introduces specific properties like furColor and a method accessReproduction utilizing a private method #reproduce for mammals.

## Examples:
# Create instances of each class and observe their behavior:

```javascript
Copy code
const butterfly1 = new Arthropod("Butterfly", "No backbone", "Forests", "Painted Lady","They have two pairs of
membranous (transparent) wings that are covered with tiny scales which give color, rigidity, and strength", 6);
const fish1 = new Fish("Fish", "Backbones are Present", "Water", "tilapia",
"Fish have gills that allow them to absorb oxygen from water and release carbon dioxide...", "Fresh Water");
// ... (create instances for other classes)

butterfly1.move(butterfly1);
butterfly1.reproduce(butterfly1);
fish1.move(fish1);
fish1.reproduce(fish1);
// ... (invoke methods for other instances)```







