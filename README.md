# 0x00. AirBnB clone - The console

In this project I covered the following concepts;

### Welcome to the AirBnB clone project!


Writing a command interpreter to manage this AirBnB objects.
This is the first step towards building my first full web application: the AirBnB clone. This first step is very important: during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…


Putting in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
Creating a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
Creating all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
Creating the first abstracted storage engine of the project: File storage.
Creating all unittests to validate all our classes and storage engine

## What’s a command interpreter?

We have the following;

Creating a new object (ex: a new User or a new Place)
Retrieving an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Updating attributes of an object
Destroying an object