# Code conventions I practice

## Naming

### 1. Use consistent naming schemes.

It will be easier to read and understand as opposed to no defined scheme.

### 2. Classes and files containt classes should be in PascalCase.

This is just the norm for programming, mainly.

### 3. Variables should be in camelCase.

This is just the norm for programming, mainly.

### 4. Flags and enums should be in MACRO_CASE.

Macro case ensures that you know the difference between flags/enums and regular constants/variables.

### 5. Types, and enums should be in PascalCase

Types and enums are significant and act like classes in some cases. Therefore, they should be named the same way as classes.

### 6. Prefix interfaces with `I`.

This is just the norm for programming, mainly.

## Refactoring

### 1. Refactoring old code to the newest specification.

This applies to everything. If there is a new feature in the newest specification at the time of writing the code and shortens existing code, use it.

### 2. Refactor classes into separate files.

If you have a class that has methods (excluding the constructor), move the class to another file and import it.

### 3. New lines after every group of related statements.

Calculations and retrieval/storage should be separated by empty new lines. Do not clump things together because it would be hard to understand.

### 4. Function declarations using the keyword should go at the bottom.

Function declarations at the bottom do not clump up your code and is easier to manage and debug.

### 5. Refactor similar global functions, objects, and constants into one file and import them.

This is to save space and make your code easily manageable and easy to understand.

### 6. Use a consistent pattern everywhere, in everything.

If you use consistent patterns, it will be easier to debug unpredicted things.
