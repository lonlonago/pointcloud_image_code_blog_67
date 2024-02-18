A few days ago, while chatting with a young man, he discovered a problem. He started learning Python from scratch, and after learning the basics of lists, dictionaries, and functions, he began to advance in the direction of crawlers. As a result, it took him more than a month to learn nothing, but it was difficult to move an inch. 

![avatar]( 60d267e152ca45608ca33d14e67d3c4e.jpg) 

In fact, the main reason for this problem is that I did not learn Python introductory knowledge well. By Python introductory knowledge, I mean not only basic knowledge such as lists, but also advanced programming content such as object oriented and process threads. 

This may be because beginners don't know how to lay the foundation, and unfortunately, the selected learning resources do not provide a good understanding of advanced programming, which makes it difficult to learn later. Haste is not enough, so for those who want to learn Python crawlers and other directions, I personally think they should learn the introductory knowledge first. 

Today, I wrote a teaching article about Python advanced programming. After you have learned the basics such as lists, learning the content of this piece will make your progression easier and smoother! 

Let's take a look at what Python advanced programming includes: 

![avatar]( f574d764f2eb44e69d52651a44b0da67.png) 

##  First, object oriented programming 

###  ➿(A) object oriented thinking 

Object-oriented is an abstract programming thinking that is shared by many programming languages. Python is a pure object-oriented language that can be understood as focusing on how to solve problems rather than studying how to implement them. 

Object-oriented and process-oriented are two different ideas. Object-oriented programming languages include Python and other languages, while procedural programming languages include C and other languages. The programming thinking in writing code is different. 

![avatar]( 2755d0fbfca546f5947d684ee270c46a.jpg) 

To understand these two ideas, take laundry as an example. 

>  Washing clothes by hand is generally dry like this: find a basin - put water - add washing powder - soak clothes - scrub - wring out - rinse - wring out - dry.

This is a process-oriented thinking. Once you don't know what to do in the middle, you won't be able to wash your clothes well. For example, if you don't know how to scrub your clothes, you won't be able to wash them cleanly. For example, if you don't wring them out after scrubbing, you can directly dry them, resulting in water on the ground. If a certain link goes wrong, it won't achieve the desired laundry effect. 

>  Washing clothes in the washing machine is generally dry like this: turn on the washing machine - put the clothes in - add washing powder - press the start button - dry.

This is an object oriented thinking. You don't need to know how the washing machine washes after putting the clothes in. You just need to know how to pour the washing powder after putting the clothes in and then press the button. 

![avatar]( 99c16e9b71704c5c8203e1eed9e2d7ed.gif) 

Similarly, in programming languages, the performance is different. When writing code in C language, you have to pay attention to your memory and other low-level things, but when writing code in Python, we rarely pay attention to the low-level things. The focus is on what method to use to solve the problem. 

Before we get into the code, there is a bit of a conceptual thing that needs to be understood. After understanding these basic concepts, we can better enter object oriented programming. 

![avatar]( 8cb26f456d674623a1ba8d6f610deca6.jpg) 

###  ➿Two important concepts of object orientation: classes and objects 

These two concepts may be easier to understand together, and can be simply understood as classes are templates for generating objects. 

We mentioned the example of the washing machine above. If the washing machine is an object, then the blueprint for making this washing machine is a class; if the egg is an object, then the hen is a class; if the dog is an object, then the dog is a class. 

In Python, everything is an object, variables are objects, functions are objects, strings, lists, tuples, and so on are all objects. 

![avatar]( f6ccb90aba4348658e08a648add36add.jpg) 

(1) Composition of objects: object = property + method 

Objects are composed of properties and methods. Properties can be understood as what an object has, and methods can be understood as what an object can do. 

(2) What are the characteristics of the object's properties? 

For example, if a washing machine is an object, then the washing machine has color, and color is an attribute, but color is an abstract thing because it can be red, white, black, and so on. 

For example, if a computer is an object, then the computer has a hard disk, and the hard disk is a property of the computer, so the property of the object can be another object. 

For example, the mouse is an object, the mouse wheel is an object, and the microcontroller inside the mouse is an object. You will find that the large object of the mouse is composed of multiple small objects. 

![avatar]( 572e1018fe2949eda113bf74982286aa.jpg) 

(3) Methods of the object 

There is a rule to understand first. The methods of an object can be called by themselves or by other objects. I will explain in detail later. 

Here we will not talk about code for the time being, because we must first talk about class knowledge in order to better understand the classes and objects in the code, which will be discussed below. 

As mentioned above, a class is a template for generating objects, so a class is an abstraction of an object, and an object is a materialization of a class. 

Since object = property + method, the same is true for class = property + method. 

(1) Create a class 

How to create a class: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, create a student class and use it to create objects 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

In fact, when creating an object of the Student class, the following three lines of code can be written as follows, with the same effect: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Let's go back and understand what properties and methods are from the perspective of combining code and concepts. 

Class attributes refer to what is in the class. For example, there are name and age in the class, so name and age are attributes of the Student class. 

The class method is what the class can do. For example, the class has the function learn (self), which can execute "the student's learning method has been called", that is, what the class can do, so the function learn (self) is the method of the class. 

![avatar]( c7cb465ad1c9488f831991c23bfe48a3.jpg) 

We have previously introduced the properties of objects and classes, so let's take a look at the differences and characteristics between the two. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, create an object, view the default init execution, and pass multiple values; call a method of a class to confirm that the method was called and execute the passed value. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
###  ➿Three characteristics of object oriented 

Three characteristics: encapsulation, inheritance, and polymorphism. 

1. Objects have clear boundaries, and properties and methods are protected within the boundaries. (security) 

2. The strength of the package is moderate. 

3. Principles of encapsulation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Inheritance is the relationship between a parent class and a child class, such as the dog class and Erha, the dog class is the parent class, and Erha is the child class. 

(1) Define the form (the complete form of the class) 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(2) Superclass: base class, superclass 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(3) The characteristics of inheritance 

Example: Invoking the properties and methods of the parent class with an object created by a subclass 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
A child class can inherit from multiple parent classes. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Note: Multiple inheritance has both advantages and disadvantages. The advantage is that it enhances scalability. The disadvantage is that it is easy to confuse logic after complex inheritance relationships, making it difficult to understand. It also takes up a lot of resources. For example, the famous diamond inheritance problem mainly involves the MRO and C3 algorithms. If you don't understand, you can Baidu it. 

(4) Method coverage 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(5) Method overloading 

Multiple methods (functions) with the same method name appear, and the method is overloaded by default value in Python. 

![avatar]( 1e813d480ba049e387a2ce3929d55dfd.jpg) 

Polymorphism: A class of things has multiple forms, which is a way of using objects. Subclasses overriding the methods of their parent classes and calling the methods of the same parent class of different subclass objects can produce different effects. 

For example, taking Honor of Kings' selection of heroes as an example, the hero class (Hero) is the parent class, and there is a method called stroke (skill) in the parent class; Cheng Yaojin and descendants are two subclasses, and there is also stroke in the two subclasses; the caller is another parent class, and there is a method to select the hero. The method needs to call the stroke class method, and finally call different subclasses (Cheng Yaojin or descendants) objects to get different skill descriptions. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Polymorphism: Send different messages to different objects, and different objects will respond differently when they receive the message. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
##  Modules and packages 

###  👳(I) Modules 

Module refers to Python's program files (source files). The file name of the module is the module name plus .py, which contains Python object definitions and Python statements. Module contains defined functions, classes, and executable code, etc. Generally, do not modify the module to avoid module failure. 

In Python, module calls are allowed in the form of imports. Modules in Python are also objects. All global variables defined in a module become attributes of the module after import. 

Syntax 1: import module name 

If you want to import multiple modules, you can use only one import to import multiple modules, separated by commas, but in Python's PEP8 style, this is not recommended, so if you want to import several modules, write several imports to import them one by one. 

Example: Import the math module and call the function of sqrt () to square 9 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
As a reminder, operations in Python return a float type by default, so it is 3.0. 

Syntax 2: import function 1 from module name, function 2 

Note that the functions here are not followed by parentheses. 

Example: Import the math module and call the function of sqrt () to square 9 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Syntax 3: import from module name 

Under normal circumstances, this syntax can import all the functions of a module. When you want to use multiple functions of a module, you don't need to write them one by one. I won't give an example here. They are all the same. 

Attention: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: (This example requires reading the following custom module to understand) 

A new module called module1 has been created, and the module code has two functions: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Import all the methods in the module using Syntax 3 in another Python file: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is only printed out fun1, and then an error is reported, indicating that fun2 () is not defined and cannot be recognized. This is because 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Some modules or function names within the module are relatively long, which is inconvenient when used multiple times. You can customize the name of the module or function. 

1. Module custom alias: import module name as alias 

Example: Customize the time module to alias t and use it. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
After 3 seconds of execution, the program outputs: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
2. Function custom alias: import function name as alias from module name 

Example: Import the time module and customize the sleep () function to the name s 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
After 5 seconds of execution, the program outputs: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Everyone can generate custom modules to call. Custom modules are Python files, and the Python files created when we write code are equivalent to one module. 

Note: The called module should be placed in the same directory as the current Python file as much as possible, otherwise the folder must be declared before importing. 

Example: Customize a module and call it in another Python file. 

Create a new Python file named module1 with the following code: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Create another Python file in the same directory and call module1.py this module: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Running the current Python file results in: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Each module is executed by default when it is imported, but at the same time there is a lot of dogfooding code inside the module. In order to avoid executing the test code inside the module when importing the module, a method is involved: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
This method can realize a function, if executed in the module, the code of executable code 1 will not be executable code 1 when other files are imported into the module, so the tests inside the general module are placed in the code 1. 

The magic point is that __name__, the result of its execution in the current file is __main__, and the result of execution when other files are imported is the module name, so take advantage of this, use the if statement to determine whether the module is executed in the current file or is imported. 

Example: 

Create a new Python called module1 as a module with the following code: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Create a new Python file and import the module1.py module you just built: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The result is different when the current file is executed and when it is imported, so it becomes the dogfooding method of the module. 

Note: In the custom module, it is not recommended to write while cycle, otherwise the while cycle in the module has been executed during the import process, and it may not jump out, that is, the module has been imported, and other code cannot be executed. 

###  👳(2) bag 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Features of the package: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Create a new project file in the Pycharm software. After the creation is completed, open Pycharm to create a project folder → click the folder → right-click the pop-up option → New → Python Package → complete the creation. The new folder created is the package, and the init file is automatically created in it. 

![avatar]( 9c11db668a044f929f462dee134c57d5.png) 

There are two main types of conventional import methods. 

Method 1: import package name. module name. target 

Method 2: import package name, subpackage, module name, target 

The targets mentioned here can be variables, functions, and other objects, as will be discussed below. 

Form of use 1: Regular use 1 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: Create a package and use it in another .py file, requiring that the .py file not be included in the created package. 

Step 1, open Pycharm to create a new project, create a package, named demo, create a new .py file in the package, named my_module, the code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Step 2, open another .py file and import the created package 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Form of use 2: Regular use 2 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: I will use the demo package created above, modify the code directly in step 2, and use this new way to import the package and use it. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The execution result is the same. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Usage Form 3: Create another alias and use it 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
In the above usage form 1, some people may find that it is not very convenient to use the imported module, and the package name and module name are required. Can it be simpler? Of course, you can directly give another shortened alias to the module in the package, and then use the alias directly. 

Following the example of using Form 1 above, I will not change Step 1 here. I will directly create another alias in Step 2. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The result is the same, but using aliases is much more convenient if the code is longer. 

Of course, you can also use Form 2 to import the package and alias it. Just use an alias when using it. I won't give an example of this method. You can try it yourself. 

Usage 4: Import a function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Here I also use the already created package and use it directly in another .py file. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Usage 5: Import all functions 

When importing the module, we introduced the import * method to import all the functions in the module. Here, you can also enter all the functions of the module in the import package. 

For example, there is a module called "hhhh" in the package named "demo". The code of the module is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Then we call it in another .py file; 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
6. About all uses 

The use of __all__ has been introduced in the module, which is to control the list of functions that can be imported, but in the package, __all__ is to control the list of modules that can be imported, that is, to declare which modules can be imported. 

__all__ inside a package are declared in __init__ file, not in which module. 

For example, there are multiple modules in a package, and all declared modules can be imported, and those that are not declared cannot be imported. 

Step 1, there are two modules called hhhh and my_module in the package named demo, but in the int file it is declared that only the hhhh file can be used. The code of the int file is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Step 2, import the hhhh and my_module modules in the demo package in the new .py file: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Execution result: 

![avatar]( 25dfe63d1afe46d88b875ce537b208ec.png) 

Obviously, although all modules are imported with *, the hhhh modules declared by all can be used, and the my_module modules not declared by all cannot be used and cannot be recognized by the system. 

###  👳(III) The role of modules and packages 

1. Improve the reusability of your code. You are not the only one who can use easy-to-use code, but many people can reuse it. 

2. Improve the readability of the code. If all the code is placed in a .py file, the code will be too long, which increases the difficulty of understanding and maintenance. Therefore, some commonly used code can be packaged into packages and modules, with a literal name, and used directly when needed. This reduces the number of codes and improves readability. 

3. Reduce code redundancy. For some methods encapsulated in the module, we can directly use them for parameters. There is no need to write the methods again, which takes up memory and reduces code redundancy. 

###  👳(Iv) Installation of third-party libraries 

Although Python has many built-in modules and packages, it is not enough to use only built-in modules. After all, built-in modules are limited, and we often use third-party libraries. It is necessary to learn how to install third-party libraries (packages) at this time. 

Today, we will introduce three installation methods for third-party modules and packages. 

You can download and install the third module and package through the package management command pip, provided that the Python you install is installed in the way I mentioned in the article [Python Basics Introduction] earlier, and all options are checked, so that you don't need to configure environment variables. First, check if your pip works. 

>  Method: WIN + R calls up the running window → enter cmd → pip can be used if the following pip information appears 

![avatar]( 2e25d40c315545f694300f3addced1dc.png) 

  If the scarlet letter prompts "pip in cmd is not an internal or external command, nor is it a runnable program or batch file", then you can manually configure the environment variables. If it doesn't work, go back and follow the steps I said to install Python to reinstall it. 

Returning to the question of how pip installs third-party modules and packages, we must first know the name of the third-party modules and packages we want to install, such as Pillow, a third-party library that is a very powerful tool library for processing images in Python. The installation method is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
![avatar]( 2c3368f1c2ba4892bd28e63e9decc337.png) 

Sometimes there will be a lot of scarlet letters prompting that the download failed. This is normal. The reason may be: 

>  (1) The .pip version is too low, upgrade the pip version and enter in the black window: python -m pip install -U pip 

>  (2) The network is not good, just download it a few more times. 

Installing via pip doesn't require opening the software, but we can also install via Pycharm as follows: 

>  Click File → Settings → Project: Project Name → Python interpreter → Click + → Enter the name of the package you want to install, select the one you like → Click Install Package → Wait for download and installation 

![avatar]( f4de08b43dd34e229d9c29dd04437a8d.png) 

 ![avatar]( 05f48ab2a8984301a7f0106296ed8f13.png) 

 ![avatar]( 2ce4335cce9c4063951ed37487d2b805.png) 

You can search and download the package you want through the official website and other channels. Official website: https://pypi.org/, search for the third-party library you want to download, such as the library Pillow, and search directly: 

![avatar]( 6fc855aaee5542d280ac9835bb1106d7.png) 

Then select the file you want to download, such as Pillow 8.3.2, enter the download page, and click Download files. 

![avatar]( 74154c816ac34fbca10cd0a04c38c0ab.png) 

 ![avatar]( 9ed44106cf5541679a12e92e28dcff49.png) 

 ![avatar]( 9649a983309d406ba533bee70152e544.png) 

  There are many versions and models after entering. It is recommended to choose the version that matches you, otherwise it may not be installed. Pay attention to the number of Python versions, systems and computers here. For example, my Python is installed 3.9.6, so I placed the file Pillow - 8.3.2 - cp39 - cp39 - win_amd64. Whl. After downloading, WIN + R opens the command line and enters CMD. Enter the file name under the pip install file path in the black window. For example, the path I stored after downloading is D:\ Google Chrome, so the code I entered in the black window is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Then enter to install and wait for the installation to complete. 

![avatar]( 6f8b70ce71c043e59a44b5a3468d7633.png) 

##  III. Document processing 

###  💼(I) Definition and operation of the document 

Computer files usually refer to the collection of information stored on the computer's hard disk as a carrier, mainly in the form of video, audio, pictures, and documents, such as executable files.exe, document file.txt, web file.html, and so on. 

![avatar]( fa8b9443bedc46acab1a7623bdf75635.jpg) 

###  💼(2) Basic operation of the document 

In reality, our operations on files can be roughly summarized as "open → operate (read, delete, modify, etc.) → save → close", which is still the case in Python. Before starting file operations in Python, let's learn a few methods. 

1.open (name, mode) ---- Open file 

This is the Python method of opening a file, which is used to open a file and return a file object. 

Name refers to the file name, which must be written in full. What is written in full? It is to write clearly, storage path + file name + suffix. 

Why do you need to write so much? Because even under the same storage path, there may be more than one file with the same file name. As long as the suffix is different, the computer allows the existence of files with the same name, so if you don't write it all, the computer doesn't know who you are referring to 

Mode is the mode to open the file. The default is r, which is the read-only mode. There are many modes of mode, such as reading, writing, etc., which we will talk about later. 

2. write ("content ") ------ write 

As the name suggests, it is to write content to the file object. 

3.read () ------- read 

To write content to the file, you can write numbers in parentheses or not. If you don't write, the default is to read the entire content. Writing numbers means reading X characters. For example, read (6) reads 6 characters of the file object. 

4. close () ------ close the file 

The method of closing the file, if you do not close the file after the file operation, the file will always be open and operated on, which will consume memory. 

5. Cases 

After understanding these 4 basic methods, let's start with a small case: create a new project, then create a Python file named "file" for writing code, and then we write "hello world" to a .txt file called "file 1" by writing. The code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
As mentioned earlier, the open () method returns a file object, so let's use f to receive it. This is the pre-run interface: 

![avatar]( d64a8cb2968b4ab58c15f0fbe2932ff9.png) 

After running: 

![avatar]( 55c5386c2faa4583a1b32ff4bae272c7.png) 

After running, a new file named "File 1.txt" is generated, and after opening it, we can see what we entered. When writing, if the file does not exist, one will be created by default. 

Similarly, we can also perform read operations on this file: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
This is the most basic file operation process. 

It should be noted here that when open (name, mode) is written at the beginning, mode already determines what operations you can do, that is, if you start writing code with: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Then if you want to write () later, an error will be reported, because the r read-only mode is declared in mode, so you do not have write permission. Please pay attention to this. 

6. other modes of operation 

There are many operation modes in mode, let's take a look at them in a table: 

The pointer can be understood as a cursor here. Where it is, your operation begins. 

For example, create a new .txt file named "test", write aaa to it for the first time, and write bbb to it for the second time. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
###  💼(III) Methods and attributes of the document 

1. Object properties of the file 

There are three commonly used methods for viewing the properties of file objects: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: Operate on the file (at will), check the file name, operation mode, and whether to close it. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
2. Object method of file 

There are many file methods, such as read () and write (), but there are still some common methods to master, such as the following: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: Write aaabbbccc to the test.txt file and output the contents of the file as a list. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
###  💼(4) OS module 

The os module is a module used to access the operating system, and it is often used when performing file operations. Modules need to be imported before use. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
1. Regarding the function of the file 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: Existing file test1.txt, modify it to test20.txt. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

![avatar]( 62246f9d25b64e0e9674be061771ca3b.png) 

2. Functions of folders 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: Create a new folder in the existing folder venv. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

![avatar]( b0baa7788daa48cab2871b139e230dfa.png) 

##  IV. Abnormal 

###  ⚡(I) Definition of an exception 

An exception is an event that occurs during the execution of a program and affects the normal execution of the program. In general, an exception occurs when Python cannot handle the program properly. 

For example, I only wrote one variable a in the code, and when I run the program, pycharm cannot recognize this variable, so an error is reported, indicating an exception. 

![avatar]( 8adc7d465fbd4c0bb2e8ceea29f1a878.png) 

###  ⚡(2) Handling of exceptions 

Therefore, we need to master the methods of handling exceptions. There are many ways to handle exceptions. Let's take a look at them one by one. 

It can process the code that may be wrong, and the red font that reports an error after processing will be converted into a short, normal font, which is used as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Example: Direct printing of variable a will generate an error. 

![avatar]( 6c531a7ed4c843c6b2460d778fc0246c.png) 

After tyr-except processing: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run it again to see the effect: 

![avatar]( 468ad28097274201a57c698debd24f06.png) 

The red error message has become shorter and the color is normal. Does this abnormality seem more comfortable? 

Here, tyr-except does not affect the execution of the code. If your code does not report an error, even if you write tyr-except, it will only execute the try line of code. If there is no error in that line of code, it will not execute the code inside except. 

For example, let's take a normal one: 

![avatar]( 9e011e9756a545d8b5644cbbf33c853a.png) 

This method is similar to the previous try-except writing method, except that an except is added later, which can be used to determine a variety of possible error situations. 

For example, there are two lines of code that might report an error, two different types of exceptions, but don't want it to go viral. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

![avatar]( 5b766e0b98924f0abdc82426c29abaee.png) 

Although the error is reported, there is no red. Here, pay attention to the two ways of writing except. 

The try-except writing method is very flexible. We can also use tuples to include exception types that may report errors to avoid writing multiple lines of except, for example: 

![avatar]( 70ff6fd15fe5432db08b0e8ba3ec6205.png) 

If there is no exception, execute the code in else, for example: 

![avatar]( b5048b15d48440da8180452e195a8d67.png) 

No matter whether the code has an exception or not, the code in finally will be executed at the end. For example: 

![avatar]( f310461c763648de917ff645cd8d1d2a.png) 

In fact, you can not add the error type after except, because the system will default that the error behind is of type Exception, which is a top-level class that contains all error types. 

![avatar]( 4cb0a47e6ae14b8781ea9af7bed1ab65.png) 

###  ⚡(III) Custom exceptions 

Have you found that when we went to do basic exception capture earlier, we had to write a try-except every time there was a possibility of error. What if there were multiple possible errors? Do we need to write multiple try-except? Or theoretically, the code can run, but I want to set a rule that any behavior that does not meet my rules will cause an exception. For example, if the password length exceeds the length specified by me, I want the program to cause an exception. 

Custom exceptions can be used to raise an exception (throw an exception), which is raised by the keyword raise. 

For example, to simulate the situation where a user enters a password, the password entered by the user cannot be less than 6 digits. Customize an exception to detect whether the password entered by the user meets the regulations. If it does not meet the requirements, an exception will be raised, indicating that the current password length and minimum password length cannot be less than 6 digits. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

![avatar]( f0f44fd55d2642c7ab58374a3b2dfc21.gif) 

From the above code, we have used the knowledge of classes and instance objects in the previous object oriented section. If you forget it, please review it quickly. In addition, we also combine the previous try-except and our keyword raise to cause exception capture. 

##  V. Regular expressions 

###  ✈️(A) re-module 

Before we talk about regular expressions, we must first know where to use regular expressions. Regular expressions are used in the findall () method, and most string retrievals can be done through findall (). 

1. Import the re module. Before using the regular expression, you need to import the re module. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
2. the syntax of findall (): 

After importing the re module, you can use the findall () method, so we must be clear about the syntax of findall (). 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
It is not difficult to see that findall () is composed of a regular expression and a target string. The target string is what you want to retrieve, so how to retrieve it is performed through a regular expression, which is our focus today. 

The result returned after using findall () is a list of strings that meet the regularization requirements 

###  ✈️(2) Regular expressions 

(1) Ordinary characters, most letters and characters can be matched by themselves. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(2) Metacharacter 

Metacharacters refer to special characters such as .^ $ ?+ {} \ [], through which we can personalize the search of the target string and return the result we want. 

Here I will introduce to you 10 commonly used metacharacters and their usage. Here I will give you a simple summary for easy memorization. The following will explain the use of each metacharacter one by one. 

![avatar]( 8c37aa9d37e14e9880b384e5b85721e3.png) 

** 1️⃣ []** 

[] 的使用方式主要有以下三种： 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The output is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, to select the abc element in the string "abcabcaccaac": 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The output is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, to select "caa" in the string "caabcabcaabc": 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The output is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Note: When in the first position of [], it means that everything except a is matched, such as changing the position of a in []: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
2️⃣^ 

^ is usually used to match the beginning of a line, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
3️⃣ $$is usually used to match the end of a line, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
4️⃣ \ 

After the backslash, different characters can be added to represent different special meanings. Common ones include the following three. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The output is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
\ can be escaped into normal characters, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
5️⃣ s 

Match any whitespace characters such as: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
6️⃣ \w 

Matches any alphanumeric and underscore, equivalent to [a-zA-Z0- 9_], for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
7️⃣ {n} 

{N} can avoid repeated writing. For example, we wrote\ w 3 times when we used\ w earlier, but here we need to use {n}. N represents the number of matches, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
8️⃣ * 

* Means zero or more matches (as many as possible), for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
9️⃣ + 

+ means match one or more times, e.g. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
🔟 . 

. is a dot, which is not obvious here. It is used to manipulate any character other than a newline character, such as: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
1️⃣ 1️⃣ ？ 

? means one match or zero 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Pay attention to greedy and non-greedy patterns here. 

Greedy pattern: Match as much data as possible, expressed as\ d followed by a metacharacter, such as\ d *: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Non-greedy mode: Match as little data as possible, expressed as\ d followed by?, such as\ d? 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The output is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
1️⃣2️⃣{M, n} m, n refers to a decimal number that is repeated at least m times and at most n times, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Add? means to match as little as possible 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
There are other flexible ways to write {m, n}, such as: 

Regarding the commonly used metacharacters and how to use them, let's take a look at the other knowledge of regular rules. 

###  ✈️(3) The use of regular rules 

In Python, the re module can compile regulars through the compile () method, re.compile (regular expression), for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The use of regular objects is not only through the findall () method we introduced earlier, but also through other methods. The effect is different. Here is a simple summary: 

(1) findall () finds all strings that re match and returns a list 

(2) search () scans the string to find the position where the re matches (just the first one found) 

(3) match () determines whether re is at the beginning of the string (matches the beginning of the line) 

Let's take the example of the object returned by compile () after compiling the regular. Instead of findall (), let's use match () to see how the result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
It can be seen that the result is a match object, the starting subscript position is 0~ 13, and the match is 010-123456789. Since the object is returned, let's talk about some operation methods of this match object. 

Here are the methods first, and I will give examples later. Common methods of using Match objects are as follows: 

(1) group () returns the re-matched string 

(2) start () returns the starting position of the match 

(3) end () returns the position where the match ends 

(4) span () returns the position of a tuple: (start, end) 

Example: Use span () to operate on the object returned by search (): 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The result is: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
In addition to the findall () function introduced above, there are other functions in the re module to provide an introduction: 

(1) findall () returns all the strings that match according to the regular expression. I won't say much about this. I have introduced it earlier. 

(2) sub (regular, new string, original string) The function of sub () is to replace the string, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(3) subn (regular, new string, original string) The function of subn () is to replace the string and return the number of replacements 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(4) split () split () split string, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
##  Process thread 

###  🔰(1) Multitasking operating system 

The operating system can perform multiple tasks, such as our Windows system. In addition to the few tasks currently being performed that you can see, there are also many tasks being performed in the background. You can use the Ctrl + Alt + Del keys to call up the task manager and take a look. 

![avatar]( 596d59cae7044c06a4df3b00fe1f9039.png) 

My computer configuration often sees the properties of a processor with several cores. For example, my computer has 12 cores, which means that the computer can execute up to 12 tasks simultaneously and run up to 12 processes simultaneously. 

![avatar]( 4c762a939ece4a0e919b019bb37a3195.png) 

But why are our computers capable of running hundreds of tasks simultaneously? 

![avatar]( dc814973184d439bb2b7278bcf0cf0ff.png) 

In fact, this is due to the task scheduling of the operating system, most operating systems are scheduled in the form of preemptive time slices. The system switches between multiple tasks very quickly in an extremely small amount of time. For example, an 8-core operating system can theoretically only execute 8 tasks at the same time within 1 second, but the system may switch between hundreds of tasks within 1 second, A task executes, B task executes, C task executes... As a result, many tasks can be executed within 1 second, resulting in hundreds of tasks that are visible to the naked eye being executed all the time. 

The term is "macroscopic parallelism, microscopic serialization," and in fact computers can only perform no more tasks than the number of cores configured in extreme time, and 8 cores can only perform 8 tasks. 

![avatar]( 53ae334ced4440d082f1e17ea70225a3.jpg) 

Since we talk about tasks, a process is a task, and a process is equivalent to a task, which is the smallest unit of resources allocated by the operating system. In Python, you can use a process to achieve multitasking, and a process is a way to achieve multitasking. 

The multiple subtasks of a process are called threads. Threads are the smallest unit of execution of a process. A process can have many threads, and each thread performs different tasks. 

![avatar]( 819fc84886574ed08f067480bb5d3cda.jpg) 

Python supports both multiple processes and multiple threads. Next, we will start to learn about Python's processes and threads. 

###  🔰 (2) Python's multiprocessing (package) 

If you use multiple processes, your Python code is executed line by line from start to finish, which is essentially executing one process, which should be well understood. 

To make more use of CPU resources, we can make use of multiprocessing. Here is a Python multiprocessing package that is commonly used in multiprocessing. It has many functions, such as child processes, communication, sharing, and execution of different forms. Let's learn about some commonly used ones. 

Process is a process class in multiprocessing, through which multiple processes can be realized. Let's take a look at its usage first, and we will have practical examples to describe it later. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
There are many methods in Process, the most common of which is the start () method to start the process. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, the code written is as follows. I want to see the effect of calling functions with and without multiple processes enabled. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
When multiple processes are not started, the execution effect is as follows: 

![avatar]( e44d56851d28415f9f3a3725c0473fb6.gif) 

As you can see, this is a very normal running situation. The program runs from top to bottom, line by line. If the three loops in music () are not completed, they will not execute the movie (). If these two functions are not completed, they will not execute the last line of print ("The main process has completed execution"). 

Let's take a look at adding multiple processes to the code in the above case: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Code I added an if statement to determine __name__ this, why? Because in the Windows system, multiprocessing this package will occur recursive phenomenon, that is, will be repeatedly executed between "import module - call module", do not believe you can remove the if statement, put all the code inside the outside to execute will report an error, this is a phenomenon that will occur under the Windows system, mac, linux and other systems do not need to add ifl to judge. 

About __name__ = "main" this knowledge point I have talked about in the initialization of modules and packages, if you don't understand, you can go back and take a look. 

Run effect: 

![avatar]( 9adfbde4ada8429cb6365b3b92d16c8c.gif) 

It can be seen that after the process is started, there are three processes running at the same time when the code is running. One is the main process that executes from top to bottom, and the output "The main process is completed" is executed below. The other two child processes execute the music () and movie () processes. Judging from their execution speed, they are running at the same time, so they don't have to wait for the code in one of the functions to execute three times before starting the second function. 

The same code, your execution effect may be different from mine, because the effect is randomly assigned according to the current state of the system, but it does not affect the fact that you can see that its result is multi-threading. 

Finally, let me add that we mentioned earlier that there are args and kwargs in Process that can be passed as parameters. Args are passed as general parameters, and kwargs are passed as parameters in the form of dictionaries. Let's take the above code as an example to pass more parameters. 

![avatar]( 4faa568f48a84f9ca6c5ee4ccb984e0b.png) 

We mentioned earlier that there are multiple processes performing tasks at the same time when the code is executed, so how to check the number of the current process to know which processes are currently running? Which are the main processes and which are child processes? There are three methods. Let's take a look at the methods first, and then use them together with examples. 

(1) Get the number of the current process: 

You need to use the getpid () method in the os module, which is used as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(2) Get the name of the current process 

Here is still the multiprocessing package, which has a current_process () method, the usage is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
(3) Get the number of the current parent process (main process) 

Which parent process does the child process belong to? This uses the getppid () in the os module, and the usage is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
![avatar]( 17c59d2259a143d691c7b0ca8804e0eb.jpg) 

Then we have seen the method. Based on the example just now, let's get and print the name, number, and number of the parent process of the current process. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

![avatar]( 266b9c6c438b491ca45829a4e740d3c2.gif) 

The number and name can be printed as long as we use the get thread method. 

###  🔰 (3) Multithreaded Threading Module 

Multiple processes can run several tasks simultaneously. As we mentioned earlier, the smallest unit of a process is a thread, so threads can also perform multiple tasks. If a process has only one task (the main process), then it can be said that there is only one thread. For example, when we do not use multiple processes to run code, we can say that there is one main process or one main thread. 

A commonly used module for multi-threading is threading, which has a class that teaches Thread. It is similar to the Process class we used for multi-process. Let's take a look at the usage first: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Similarly, multiple threads also need to be enabled, similar to the previous one. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
There is also a way to get the thread name: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
With these knowledge points in mind, let's start with an example: using a similar example to the one above to use our multithreading. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
It can be seen that our multi-threading is actually similar to multi-process, and it can also run multiple tasks. Here we also increase the use of parameters. 

![avatar]( b3cb831259f747668720524a418cb726.jpg) 

In addition to using the above methods to implement multi-threaded tasks, we can also use inherited classes to implement multi-threading. 

Example: multithreaded to print "cool" and "hair gone." 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The MyThread class is created by ourselves, which inherits from the parent class threading. Thread. At the same time, we need to write the initialization method of MyThread, and do a good job of preparation every time it is called. We have also talked about this, and we have talked about it in the previous object oriented. If you don't understand, you can look at the content of the object oriented article. 

Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
There are random effects. Your effects may be different from mine. When each computer runs multi-threaded code, whichever thread can grab the time slice will execute first. 

Multithreading can also be achieved through inheritance from the class Thread. 

##  Seven, containers/iterators/generators 

###  🚩 (I) Container 

In Python, a container is a data structure that organizes multiple elements together, and the elements in the container can be obtained one by one iteratively. To put it bluntly, its function is just like its name: to store things (data). 

The container does not actually exist. It is not a data type, but an artificial concept. It is just a concept word created for the convenience of learning. It can use the membership operator (in or not in) to determine whether the object is in the container. 

Of course, it wasn't created by me, I don't have that much ability, it was officially created, well, don't worry, I'm teaching you some weird nouns, and no one will understand it when you say it... It's called that in python. 

![avatar]( 4e65de7e7d4f41eba25846e6ef57e294.jpg) 

Common container types include lists, tuples, strings, dictionaries, and sets. 

Since the data in the container can be obtained iteratively, we have to learn a new concept: iterable objects. 

###  🚩 (2) Iterable objects 

What is an iterable object? 

In Python, an iterable object doesn't refer to a specific data type, it refers to a container object that stores elements. 

That is to say, if there is no data stored in the container, it is not an iterable object, and not all containers are iterable objects. Containers contain but are not limited to iterable objects. 

Pay attention to two points: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Have you ever thought about how the for loop is implemented internally? For example, in this example of a for loop, why can every element in the list be output? How is it implemented internally? 

![avatar]( b9a028d2f0454756b484ffe84a77aed8.png) 

In fact, the loop does two things: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Then we don't need a for loop to output each element in the list, 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Output result: 

![avatar]( a93739168dcb443a916dc1db33f9371f.png) 

It can be seen that if we remove the line of code that prints ite, the execution effect is the same as each element in the output list of the for loop. The for loop defines the range 4 times, and actually executes 1 __iter__ () and 4 __next__ (), that is to say, the essence of the for loop accessing the iterative object is achieved through this. 

Moreover, the two things that the for loop essentially does are indispensable, that is to say, if there is no __iter__ () to return the iterator first, __next () __ cannot get the element, which just shows the second point of the two points mentioned above: an iterable object cannot be iterated independently. 

There are two built-in functions that have the same principle as them and are essentially the same. It is more convenient to use built-in functions if you want to use them, at least you don't need to write so many underscores: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
![avatar]( 2fc205b9d56e48858355262021fb2e33.png) 

It can be seen that the result is exactly the same. Since iterators are mentioned, let's take a look at what an iterator is. 

![avatar]( 511a9cb2757f46879097683afe530fd4.jpg) 

###  🚩 (III) Iterator 

From the example of the for loop above, we can probably see that, 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Since this is the case, when we learned the basics of Python, we said that range () is an iterable object, so it can also generate an iterator by __iter__ (). 

![avatar]( d71df4ed7b2048f68c209a8a306bfe92.png) 

###  🚩 (Iv) Sequence 

Sequence is also an abstract concept, which includes lists, tuples, and strings. It does not exist in itself, and is also a concept created for learning. 

Iterable objects contain sequences, and since sequences contain lists, tuples, and strings, as in our previous example, sequences can be used by iter () and next (). 

Sequences can be divided into finite sequences and infinite sequences. Finite sequences have a range, for example, range (10) has defined the range, on the contrary, infinite sequences are sequences without a limited range. 

We need to generate an infinite sequence. Here, we need to use a new module, itertools, which is a collection of iterative functions for efficient loops. It has a method count () below it, which can generate an iterator without range, which can be understood as an infinite iterator. 

![avatar]( 9fdbeb032c7c4ef69f03b4769ba78be3.png) 

From this example, we can see that as long as it is executed once, next () will fetch the contents of the iterator once and retrieve them one by one. I have only written four next () here, and you will output a few more times if you write more. 

A mechanism like next () that needs to be called when is called lazy loading mechanism, also known as lazy loading; 

On the contrary, there is hungry loading. For example, the for loop will fetch all the objects in the iterator as soon as it is executed. 

###  🚩 (5) List derivation 

List derivation is related to the generator. Before talking about the generator, you need to know what a list derivation is. A list derivation is a method of generating a list. The syntax is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
I represents the object to be placed in the list, and the for loop is an expression. 

For example, let's use a list derivation to generate a list. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Using list derivation can easily generate the list we want. 

And there's lots of other flexible uses of it, like conditional judgment. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
If the following condition is determined to be true, the list can be generated normally. If it is false, the list derivation is invalid. At this time, l will be an empty list. 

There are other flexible uses, such as manipulating the previous i, such as doubling the value of i: 

![avatar]( 474e4417244c4665bef84250e73e54e4.png) 

We replace the iteration object with a string, which can also be output, but * represents the repeating operator in the string, so the effect becomes like this: 

![avatar]( 07b3e0047f2b4077a4ce120d75691783.png) 

Not only that, but we can also use functions to operate the previous i * 2, such as: 

![avatar]( 1639088b00854f39ac6102409066b1de.png) 

Overall, list derivations are a flexible way to quickly and customize the generation of lists. 

Then someone may draw inferences. List derivations are all operated with [], so if you use () to operate, will it generate a tuple? Let's take a look: 

![avatar]( 5e0763154370477bb3c97164bd8ee3f8.png) 

[] 换成（）之后，返回的是一个生成器generrator ，那么下面我们再来讲讲生成器： 

###  🚩 (6) Generator 

Generators are objects that actually exist in Python, unlike containers, which can be called directly through next (). 

The first creation method is similar to the list derivation, that is, [] is replaced by (): 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, let's generate a generator and see if we can call it directly with next (): 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
It can be seen that the generator can be called directly. So since the generator can be called by next (), then the generator is a special iterator, an iterable object. 

In addition to creating a generator in the above method, you can also create it with yield as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
For example, let's create a generator with a function containing yield: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The result is a generator, and at this point the function fun () is no longer a function, it is a generator, and as long as yield appears in the function, the function becomes a generator. 

Why doesn't the while loop keep executing? Don't worry, let's output it: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
I called it three times, so it ran three times. The while loop exists, but it doesn't work because of the lazy loading we mentioned earlier. 

When you need it, when you use the next () call, it is lazy loading, unlike hungry loading, which generates all objects in advance. If you replace it with a for loop to complete, for example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
After running the program will enter an infinite loop, has been to add 1 to a, you can try to see the effect, that is, hungry Han type loading generates an iterator in advance and calls all iterator objects, hungry Han type loading takes up resources magnifying glass. 

![avatar]( 385b2f18574c4a5bb436f40621643d11.jpg) 

Finally, a diagram summarizes their relationship: 

![avatar]( c6df2e0dba4940f49b89ba7d402f5b37.jpg) 

##  Eight, modifier 

###  🏁 (1) The concept and role of modifiers 

A decorator, also known as a decorator, is itself a function that adds additional functionality to an existing function or method. 

In summary, the role of a decorator is to add additional functionality to an existing object. 

For example, this function is a registered function, but sometimes when the user performs this operation, he is a registered user. I have already written this function and don't want to move it. Then we can add a login function to this function through a decorator. 

It is often used in scenarios with tangential requirements, such as: insert log, performance testing, transaction processing, caching, permission verification, etc. Decorators are an excellent design to solve such problems. With decorators, we can extract a lot of identical code that has nothing to do with the function itself and continue to reuse. 

![avatar]( 52fee12ad3ed4d0890da2e167b585f5d.jpg) 

The specific operation of the decorator, let's learn it slowly. 

###  🏁(Ii) The use of modifiers 

Before using decorators, we need to remember a few instructions for using them: 

(1) The keyword for a decorator is @. As long as it appears in Python code, you can think of it as a decorator. 

(2) Decorators modify functions or methods and cannot modify a class. 

(3) The decorator must appear on the previous line of the function or method being modified, and cannot be defined on the same side of the function. 

Example: 

![avatar]( a55667c8f5854d77a533af9c4ddb0fe4.png) 

Although the decorator itself is a function, its appearance is regulated. The above decorator does not appear in the first line of the modified function or method, so even the print ("Uncle Dragon") line of code cannot be executed. 

(4) The decorator itself is a function that passes the modified function as a parameter to the decorator, performs the functions in the decorator, returns the passed function object, and calls the returned function. 

These points are important, and let's deepen our understanding by exploring the various uses of decorators. 

![avatar]( 36009dafc7d84ffdaf10bfadf96d75b5.jpg) 

If the modified function is not called, the function following @is executed, and the modified function is passed as a parameter, then the return value of the decorator function can be any value. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
First of all, we can see that this is a very simple example of using a decorator, using @dec to call the dec () decorator function, while the modified function funA () does nothing. 

Secondly, we can see that the modified function funA () does not call anything, but it is passed as an argument to the decorator function dec (), so dec () needs a parameter to accept the passed value. I used a as a parameter. If you remove a, the system will report an error, because the value returned by the modified function funA () is not accepted. You can try it. 

Finally, there is one more point, the modified function funA () has not been called, have you noticed? So the decorator function dec () returns anything, the above returns None, you can return a "sick", you can return anything, let's look at the situation where the modified function funA () is called. 

![avatar]( fd5b2f6dd50b4ab1bc121b0c379db8b7.jpg) 

If the modified function is called, execute the decorator directly and pass the modified function to the decorator as a parameter, but the return value of the decorator must be the current parameter. 

Example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
There is an error, saying that string str cannot be iterated, why? In fact, the reason is that when a decorator exists and is used, the modified function is called again. At this time, the return value cannot be any value. At this time, the decorator function can only return the passed value. You can try to change the return "sick" to return a to output normally, or you can remove the line of code funA () and do not call the Hughes function, the output is normal. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Everything is normal. 

Let's take a look at the execution logic of the decorator again: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
From this running result, we can see that the modifier's running logic is: the modified function funA () is called, but it is not directly executed, but directly executes the modifier dec, and passes the modified function funA () as a parameter to the modifier dec, executes the code in the modifier function dec (), returns the code in the modified function funA () that is executed after passing the value a, and finally finishes the modified function funA () before executing the remaining code. 

I'll use a more sketchy diagram to illustrate this: 

![avatar]( 3da35bef75ab42c5ac3a02f6f8bdbc36.png) 

We talked about the basic uses of decorators earlier. There are many ways to use decorators, and you can also use function nesting. 

Let me demonstrate with a simple example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
From the running results, function nesting can also be carried out in the modified function. 

Closures are also a type of function, but they are relatively special. I will not repeat the knowledge about closures here. In [Python Basics], we have talked about closures. If you forget, you can take a look or Baidu. Let's take a look at how closures in modifiers are used. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
It can be seen that closures can also be used normally in decorator functions. 

![avatar]( 92eed7881d6d44dcadb8f04775ff8825.jpg) 

If the modified function has parameters passed, the parameters can only be passed to the embedded functions in the decorator function. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
It can be seen that although the modified function C () passes parameters to the decorator function A (), the default pass is still the object C (), the decorator function A () accepts the modified function C (), and the parameters are passed to the function B () in the decorator function A (). 

Even if you add two parameters to A (), it will not accept it and will only report an error. We have already said in the instructions for the use of the decorator, "The modified function is passed to the decorator as a parameter", so the decorator function accepts only the object of the modified function. If you want to pass parameters, then there must be other functions in the decorator function to accept the passed parameters. 

If the decorator has parameters but the modified function has no parameters, you can only use the inline function to collect the parameters. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
###  🏁(III) Python's built-in decorators 

The previous ones we talked about are all our custom decorators. In Python, there are built-in decorators. Let's learn about three common Python built-in decorators: staticmethod, classmethod, and property. 

Their function is to transform the methods in the class into static methods, including class attributes and class methods of the class. Let's take a brief look at the specific use. 

Property can change a method into a property. The modified method name must be the same as the method name below the property. Property can only be used for private properties. 

Let's make a comparison. We create a class and use the methods in the class without using properties, as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
No problem, it works fine, so let's try it with the built-in decorator property to see what's different. 

Before using the built-in decorator property, we have to add a point: private properties, properties created inside the function are private properties, and cannot be used outside the function without special treatment. Private properties are represented by two underscores in front of them. For example, the __name in the class represents private properties. Let's take a look at a simple example: 

![avatar]( d688fd8ef22f4eb2ae0c3d5abf61bee8.png) 

It can be seen that private attributes can be accessed within the class, but not externally (they can be accessed after some processing, which will not be introduced here. You can check it online). 

Returning to our built-in decorator properties, in the previous example where we did not use properties, we made a modification to add the built-in decorator properties. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
From this example, we can see that the built-in decorator property can be used for private properties, and methods can be turned into properties. For example, a.age is calling properties instead of methods. Although age () appears many times in the class, it does not report an error because of method coverage. It is also because of the existence of property that the property stipulates that the modified method name must be the same as the method name below the property. 

![avatar]( a3a4a683012f4576ab60b8b2b5bd7f6b.jpg) 

The built-in decorator staticmethod is a static method whose function is to remove the modified method from the class and become an independent function, which cannot access the properties of the class. 

Let's write a simple class first and compare it with staticmethod without using it 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
There is no problem with this. Let's take a look at using the staticmethod and add it directly: 

![avatar]( b3cfd203de7f464cb13b13d7bbc5bdac.png) 

The reason for the error is that after adding @staticmethod, the eat () method becomes an ordinary function. Although its position is in the class, it is actually equivalent to an ordinary function, not a class method. Therefore, you have to pass a value to it, otherwise the parameter self will not be passed and the error will be reported. 

The correct writing should be: 

![avatar]( b67ef6dcacb7404ebe62a0211bd7fe9b.png) 

Let's summarize this staticmethod: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
The difference between a method decorated with classmethod and an instance method is that the first parameter received is not self, but cls (the concrete type of the current class). The modified method cannot access instance properties, but can access class properties. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
From the results, it can be seen that from the objects printed by sleep () and eat (), the object passed by sleep () is the instance object b created, while the function eaten () modified by the decorator passes the class; from the point of view of eating () accessing the properties and instance properties of the class, there is no problem accessing the properties of the class, but an error is reported when accessing the properties of the instance object. 

Therefore, it is verified that the method modified by classmethod is different from the instance method in that the first parameter received is not self, but cls (the specific type of the current class). The modified method cannot access the instance properties, but it can access the class properties. 

~ 

Run result: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574529363
 ```  
From the results, it can be seen that from the objects printed by sleep () and eat (), the object passed by sleep () is the instance object b created, while the function eaten () modified by the decorator passes the class; from the point of view of eating () accessing the properties and instance properties of the class, there is no problem accessing the properties of the class, but an error is reported when accessing the properties of the instance object. 

Therefore, it is verified that the method modified by classmethod is different from the instance method in that the first parameter received is not self, but cls (the specific type of the current class). The modified method cannot access the instance properties, but it can access the class properties. 

![avatar]( 8b1c3cdba006460fa6262c4ba06fd856.png) 

 Today's sharing is here, welcome to leave a message in the comment area!  

