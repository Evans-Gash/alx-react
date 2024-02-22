# 0x06. React Immutable

## Description

This project focuses on understanding and implementing immutable objects in JavaScript using the Immutable.js library within a React environment. Immutable objects are crucial for maintaining data integrity and avoiding unintended mutations, especially in large-scale applications. By the end of this project, you'll gain a solid understanding of immutable objects, how to use the Immutable.js library effectively, and various related concepts.

## Learning Objectives

- Explain the concept of immutable objects and their significance in JavaScript applications.
- Utilize the Immutable.js library to incorporate immutability into JavaScript data structures.
- Differentiate between List and Map data structures and understand when to use each.
- Implement operations such as Merge, Concat, and Deep Merging using Immutable.js.
- Understand and utilize Lazy Seq for efficient data manipulation.

## Tasks Overview

1. **Converting into an Immutable object using fromJS**: Convert a plain JavaScript object into an immutable Map using the `fromJS` function from Immutable.js.
   
2. **Converting into Immutable using Map**: Modify a function to convert a plain JavaScript object into an immutable Map directly.
   
3. **Accessing nested elements**: Implement a function to access nested elements within an object based on a provided path.
   
4. **List and push**: Create functions to convert an array into an immutable List and to add elements to the list.
   
5. **Chained mutations**: Create Immutable Maps and apply chained mutations to modify specific values.
   
6. **Merge & concat**: Implement functions to merge and concatenate elements using Immutable.js data structures.
   
7. **Nested merge**: Develop a function to deeply merge two objects into one, handling conflicts where values overlap.
   
8. **Equality**: Create a function to compare the equality of two Immutable.js Maps.
   
9. **Lazy Seq**: Implement a function to filter and print student data based on specific criteria using Lazy Seq.

## Requirements

- Allowed editors: vi, vim, emacs, Visual Studio Code
- NodeJS 12.11.x and npm 6.11.x must be installed.
- All files should end with a new line.
- All functions must be exported.
- Tasks should be completed using Immutable.js library for data manipulation.

## Setup

To set up the project environment:

1. Install NodeJS 12.11.x and npm 6.11.x.
   
2. Execute the following script to install the required versions:

    ```bash
    $ curl -sl https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
    $ sudo bash nodesource_setup.sh
    $ sudo apt install nodejs
    ```

3. Clone the repository from GitHub:

    ```bash
    $ git clone <https://github.com/Evans-Gash/alx-react.git>
    ```

