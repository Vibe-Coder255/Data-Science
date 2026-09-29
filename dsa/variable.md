# Variable in Python 

* Local Variables: Variables declared inside a function. They can only be accessed within that specific function and are destroyed once the function finishes executing.

def my_function():
    local_var = "I am local"
    print(local_var)


* Global Variables: Variables declared outside of any function. They can be accessed from anywhere in the script. If you want to modify a global variable inside a function, you must use the global keyword.

global_var = "I am global"

def my_function():
    print(global_var) # Accessible here
