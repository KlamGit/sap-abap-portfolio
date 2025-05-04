# Task 04 – Create and Run an ABAP Class

## 💻 What I Did

In this task, I created my very first ABAP class using Eclipse and the ABAP Development Tools. I added the class to the package I created earlier (`ZS4D100_01`) and implemented the `IF_OO_ADT_CLASSRUN` interface, which allowed me to run it as a console application within Eclipse. This was my first real interaction with ABAP code execution and class behavior.

---

## 🔧 Step-by-Step Actions

### 1. Created the Class

- I opened Eclipse and navigated to:  
  `File → New → ABAP Class`
- I entered the package: `ZS4D100_0405`
- I named the class: `ZCL_0405_HELLO_WORLD`
- I gave it the description: **"My first ABAP Hello World class"**
- In the **Interfaces** section, I clicked `Add…` and typed `IF_OO_ADT_CLASSRUN`
- I selected the interface from the hit list and added it
- I clicked **Next**, selected **my existing transport request**, and clicked **Finish**

### 2. Implemented the Main Method

Eclipse generated a method stub for the interface method `IF_OO_ADT_CLASSRUN~MAIN`.

Inside that method, I inserted the following code:

out->write( | Hello World | ).

3. Activated and Ran the Class
I pressed Ctrl + F3 to activate the class.

Then I hit F9 to run it.

A new Console tab appeared at the bottom of Eclipse, and I saw the output:

Hello World
If the Console hadn't shown automatically, I would have gone to:
Window → Show View → Other → Console


🧠 What I Learned:
I now understand how to create and structure an ABAP class within a package.

I learned how to use the IF_OO_ADT_CLASSRUN interface to make a class runnable like a console app.

I practiced using out->write() for basic output.

I became more comfortable navigating Eclipse ADT for ABAP.

I saw the workflow of development → activation → execution inside Eclipse
