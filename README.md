# Code conventions I practice (when in a team)

## Documenting

### 1. Document all methods and properties.

It will be easier to use code by other people.

### 2. The description should be short and sweet.

The description of the methods and properties should explain the method or property in one sentence.

### 3. Enforce types (if you are using TypeScript) if it is not.

The compiler can be more helpful if you do this.

## Formatting

### 1. End simple statements with semicolons.

Always end simple statements with semicolons for readability and so that minifiers can actually minify your code.

### 2. Never end complex statements with semicolons.

This includes: function declarations, if statements, switch case, and for loops.

### 3. Use 4 spaces for a tab.

This is debatable, but is the norm.

### 4. If a line is longer than 80 characters, break it up.

This is for readability. The best place to break up a line is either an operator or a comma.

### 5. File names should not have spaces nor hypens.

This may cause problems with dynamic imports and it doesn't look as cool. 😎

### 6. Use spaces to separate the key from the colon in objects.

It is easier to read the values this way.

## Naming

### 1. Use consistent naming schemes.

It will be easier to read and understand as opposed to no defined scheme.

### 2. Classes and files containing classes should be in PascalCase.

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
