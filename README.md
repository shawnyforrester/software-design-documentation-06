# software-design-documentation-06
Software Design &amp; Documentation - week 06

Here's a README file for the provided Java application. This README includes an overview of the project, installation instructions, usage instructions, and the commands for generating JavaDoc, compiling, and running the application.

## README

# Java LinkedList Application

## Overview
This Java application provides an implementation of a generic container using a LinkedList. It includes the following classes and interfaces:
- `Container<T>`: An interface that defines a method to create a container.
- `LinkedListBuilder<T>`: An abstract class that implements the `Container<T>` interface to provide a generic LinkedList container and related methods.
- `LinkedListIntegers`: A concrete class that extends `LinkedListBuilder<Integer>` to create and manage a LinkedList of integers.

## Features
- Create a generic LinkedList container.
- Add elements to the LinkedList.
- Remove elements from the LinkedList.
- Print the elements of the LinkedList.
- Read integers from user input and sort the LinkedList.

## Requirements
- JDK 22.0.1 or higher

## Installation
1. Ensure JDK 22.0.1 or higher is installed on your system.
2. Clone the repository or download the source files.

## Usage

### Generating JavaDoc
To generate the JavaDoc for this project, use the following command:
```sh
javadoc -d doc -sourcepath src src/Container.java src/LinkedListBuilder.java src/LinkedListIntegers.java
```
This command will generate the JavaDoc and place it in the `doc` directory.

### Compiling the Application
To compile the application, navigate to the directory containing the `src` folder and use the following command:
```sh
javac src/*.java
```
This will compile all the Java files in the `src` directory.

### Running the Application
To run the application, use the following command:
```sh
java src/LinkedListIntegers
```
The application will prompt you to enter a series of integers separated by spaces. After entering the integers and pressing Enter, the application will sort and print the list of integers.

## Example
Here is an example of how to use the application:

1. Compile the code:
    ```sh
    javac src/*.java
    ```

2. Run the application:
    ```sh
    java src/LinkedListIntegers
    ```

3. Enter the integers when prompted:
    ```
    Enter the number of integers you want to add to the list. Please separate your integers by a space. Hit Enter when you are finished:
    5 3 8 1 4
    ```

4. The application will output the sorted list:
    ```
    Here is your list of elements:
    1
    3
    4
    5
    8
    ```

## License
This project is licensed under the MIT License.

## Author
Your Name

## Acknowledgments
- Java Documentation: https://docs.oracle.com/javase/22/docs/api/

Feel free to customize the README further as needed for your specific project requirements.
