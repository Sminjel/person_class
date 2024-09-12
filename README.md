# Person Class

## Overview

This Python script defines a `Person` class with attributes for the person's name, age, and gender. It also includes a method to introduce the person by printing a message with their details.

## Features

- **Attributes**: 
  - `name`: Represents the person's name.
  - `age`: Represents the person's age.
  - `gender`: Represents the person's gender.
- **Method**:
  - `introduce()`: Prints a message introducing the person with their name, age, and gender.

## Usage

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/your-username/person_class.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd person_class
    ```

3. **Run the script**:

    ```bash
    python person.py
    ```

4. **Output**:
   Running the script will create an instance of the `Person` class with sample data and print a message introducing the person.

## Example
Hello, my name is Smangele. I am 30 years old and I am female.

## Class Definition

The `Person` class is defined as follows:

```python
class Person:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age
        self.gender = gender

    def introduce(self):
        print(f"Hello, my name is {self.name}. I am {self.age} years old and I am {self.gender}.")

## Author

1. GitHub smangelent@gmail.com.
2. (https://github.com/smangelent@gmail.com)
