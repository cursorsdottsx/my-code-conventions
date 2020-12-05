# Code conventions I practice

## Refactoring

### 1. Refactoring old code to the newest specification.

This applies to everything. If there is a new feature in the newest specification at the time of writing the code and shortens existing code, use it.

### 2. Refactor classes into separate files.

If you have a class that has methods (excluding the constructor), move the class to another file and import it.

### 3. New lines after every group of related statements.

Calculations and retrieval/storage should be separated by empty new lines. Do not clump things together because it would be hard to understand.

### 4. Function declarations using the `function` keyword should go at the bottom.

Function declarations at the bottom do not clump up your code and is easier to manage and debug.

### 5. Refactor similar functions, objects, and constants into one file and import them.

This is to save space and make your code easily manageable and easy to understand.

### 6. Use a consistent pattern everywhere, in everything.

If you use consistent patterns, it will be easier to debug unpredicted things.
