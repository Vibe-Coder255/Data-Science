# Variable Scope in Python

* **Local Variables:** Defined **inside a function**. They can only be accessed within that specific function and are destroyed once the function finishes executing.

  ```python
  def my_function():
      local_var = "I'm hidden inside!"
      print(local_var)
  ```

* **Global Variables:** Defined **outside any function** (usually at the top level of the script). They can be accessed from anywhere in the code. If you want to modify a global variable inside a function, you must use the `global` keyword.

  ```python
  global_var = "I'm accessible everywhere!"

  def my_function():
      print(global_var)  # Works perfectly
  ```