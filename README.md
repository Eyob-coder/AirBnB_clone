AirBnB clone


Description-
This team project is part of the Holberton School Full-Stack Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.

File storage-
The folder engine manages the serialization and deserialization of all the data, following a JSON format.

A FileStorage class is defined in file_storage.py with methods to follow this flow: <object> -> to_dict() -> <dictionary> -> JSON dump -> <json string> -> FILE -> <json string> -> JSON load -> <dictionary> -> <object>

The init.py file contains the instantiation of the FileStorage class called storage, followed by a call to the method reload() on that instance. This allows the storage to be reloaded automatically at initialization, which recovers the serialized data.

Tests-	
All the code is tested with the unittest module. The test for the classes are in the test_models folder.

Authors.

Eyob Berhanemeskel        
Abenet Dessie
