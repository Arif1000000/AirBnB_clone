Synopsis
The Airbnb clone project for which we are creating a copy of the Airbnb. Only some features will be implemented and will be listed below once completed.

Features

Command Interpreter

Description
The Command Interpreter is used to manage the whole application's functionality from the command line, such as:

Create a new object.
Retrieve an object from a file, database, etc.
Execute operation on objects. e.g. Count, compute statistics, etc.
Update object's attributes.
Destroy an object.
Usage
To launch the console application in interactive mode simply run:

console.py

or to use the non-interactive mode run:

echo "your-command-goes-here" | ./console.py

Commands
|   Commands   |           Description              |    Usage      |
| ------------ | ---------------------------------- | ------------- |
| help or ?    | Displays the documented commands   | help          |
| ------------ | ---------------------------------- | ------------- |
| quit         | Exits the program.                 | quit          |
| ------------ | ---------------------------------- | ------------- |
| EOF          | Ends the program.Used when files   |               |
|              | are passed into the program.       | N/A           |
| ------------ | ---------------------------------- | ------------- |
|              | Creates a new instance of the      | create        |
| create       | <class_name>.Creates a Json file   | <class_name>  |
|              | with the object representation. and|               |
|              | prints the id of created object    |               |
| ------------ | ---------------------------------- | ------------- |
| show         | Prints the string representation of|    show       |
|              | an instance based on the class name| <class_name   |
|              | and id.                            | class_id>     |
| ------------ | ---------------------------------- | ------------- |
|              | Deletes and instance base on the   | destroy       |
| destroy      | class name and id.                 | <class_name   |
|              |                                    | class_id>     |
| ------------ | ---------------------------------- | ------------- |
|              | Prints all string representation of| all or all    |
| all          | all instances based or not on the  | <class_name   |
|              |                                    | class_id>     |
| ------------ | ---------------------------------- | ------------- |
|              | Updates an instance based on the   | update        |
| update       | class name and id by adding or     | <class_name   |
|              | updating attribute                 | class_id key  |
|              |                                    | value>        |

Tests

If you wish to run at the test for this application all of the test are located under the test/ folder and can execute all of them by simply running:

python3 -m unittest discover tests 

from the root directory.
