AirBnB Clone Project
Web Application - Front End which is the console that is the cmd module
                - Backend - will be oop that is object oriented programming concepts
                - Database for storage we will have the json module for purposes of storage
                - Testing - the unittest module
In this project, we are going to create :
Class BaseModel():-define attributes that are common
                  -define methods that are common 
Class User [BaseModel]-inherits all the base class attributes
                      -all the base class methods 
                      -declare the unique attributes and the methods of this class
Class Amenity [BaseModel #attributes

OBJECT - in python everything is object, therefore we prepare this object for storage 
    we apply concepts of -> serialization
                         -> deserialization
           We use Class FileStorage():
                         #attributes related to files
                         #methods related to files
models directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.
tests directory will contain all unit tests.
console.py file is the entry point of our command interpreter.
models/base_model.py file is the base class of all our models. It contains common elements:
attributes: id, created_at and updated_at
methods: save() and to_json()
models/engine directory will contain all storage classes (using the same prototype).

The Console application - mainly we focus on the cmd module
 - we create command prompt and command such as -> creat|show|count|destroy|update
Testing with the Unittest Module
  -> create a case that will inherent from the unittest.Test Case Class
  ->create setup and teardown functions to assign variables and update them after
