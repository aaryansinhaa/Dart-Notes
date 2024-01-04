In Dart, variables are used to store and manipulate data. Here are some key aspects of variables in Dart:

### 1. **Declaration and Initialisation:**

- Dart supports static typing, where you declare the type of a variable explicitly or use type inference. You can declare a variable using the `var` keyword or explicitly specify the type
```
- var name = "john";
- String name = "John";
```

### 2. **Data Types:**

- Dart has various data types, including:
    
    - `int`: Integer numbers
    - `double`: Double-precision floating-point numbers
    - `String`: Sequence of characters
    - `bool`: Boolean values (true/false)
    - `List`: Ordered collection
    - `Map`: Key-value pairs
    - `Set`: Unordered collection of unique values
	    
```
    // Initialisation and declaration of variables in dart
    <datatype> <variablename> = <variablevalue>;
    
    *or*
    
    <datatype> <variablename>;
    <variablename> = variablevalue;
```

### 3. **Dynamic Typing:**

- Dart also supports dynamic typing, where the type of a variable is determined at runtime. You can use the `dynamic` keyword for dynamic typing. Dynamic is just like a datatype, so when we are declaring a variable in dart with the dynamic typing we are basically assigning it with a dynamic datatype at the time of coding and assign it a datatype at runtime.
    
    
    
    `dynamic dynamicVariable = 'This can be a string'; dynamicVariable = 42; // Now it can be an integer`
    

### 4. **Constants:**

- Dart allows you to declare constants using the `final` or `const` keyword. `final` variables are evaluated at runtime, whereas `const` variables are evaluated at compile-time.
    
    
    
    `final int a = 10; // Runtime constant const double pi = 3.14159; // Compile-time constant`
    

### 5. **Scope:**

- Variables have a scope, which is the region of code where the variable is accessible. Dart uses block-level scoping.
    
    
    
```
    void randomFunction() {
			  int x = 10; // x is only accessible in this function
			  print(x);
}

```
    

### 6. **Null Safety:**

- Dart has introduced null safety, which means that variables are non-null-able by default. If a variable can be null, you need to declare it explicitly with a `?` or use the `late` keyword.
    
    
    `String? nullableString = 'Nullable';`
    

