# Exception Handling in C++
## Aim
To study about exception handling in C++.

## Theory
Exception handling in C++ is a structured way to handle runtime errors, ensuring that programs remain robust and do not crash unexpectedly. It revolves around three main keywords: `try`, `throw`, and `catch`. Code that might produce an error is placed in a `try` block. If an error occurs, an exception is "thrown" using the `throw` statement, transferring control to the nearest `catch` block that can handle the exception. This mechanism allows the program to gracefully manage errors without terminating abruptly. C++ allows exceptions of any type, though they are often derived from the `std::exception` class. Exception handling ensures that errors are addressed appropriately, and destructors for objects created during the `try` block are called through a process called stack unwinding. By catching exceptions, programs can continue running or provide meaningful feedback to the user, making the code more reliable and maintainable.

`Syntax`

    try {
    
        // Code that might throw an exception
       
    } 
    
    catch (exception) {
    
        // Handling the exception
        
    }


## Output

![image](https://github.com/user-attachments/assets/967ca2be-6bfd-4845-b3d9-1442ad7c954a)

![image](https://github.com/user-attachments/assets/ab9d2cc4-1938-43fa-882b-753afad312d2)

![image](https://github.com/user-attachments/assets/15ef5162-494b-44de-a1b1-8011faa133d0)

![image](https://github.com/user-attachments/assets/2bbb49f7-17ec-48dd-8f58-bbfb485c8641)

## Conclusion
We learnt about exception handling in C++.






