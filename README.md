# Basic Java concepts
## How compilation works
For most programming languages, the code is compiled into a mahine-language program and then can be executed. It only allows the program to be executed in the specific operating system it was designed to run, meaning, you would have to write a
new version of the same code for every operating systems you want your software to perform.

![image](https://wpbackendapi.tutorend.com/wp-content/uploads/2023/08/compilation-process.jpg?raw=true&width=50)

## Java is a hybrid language
Java doesn't follow this patttern. Java follows the 'WORA' principle: Write Once, Run Anywhere. With Java, we only have to write the code once, and it can run in any device.
This is possible beause of JVM (Java Virtual Machine). It works like this: The code you write is not compiled into a machine-language, instead it is compiled into a bytecode file, which 
is machine-independent. Once the JVM has the bytecode, it can be executed in any device, may it be Windows, Linux, macOS, mobile, etc.
That's why we call Java a hybrid language.

![java](https://smartprogramming.in/tutorials/java/images/how-java-works.jpg?raw=true&width=50)

## Variables 
Variables are one of the most important concepts in programming. Basically, it is a space inside the memory that stores data. A program is responsible for receveing, processing and outputting these data.
A variable must have a name, for us to identify it, and a value. Ex.: String name = "Jhonny"; We can acess the data "Jhonny" simply by referring to "name";

![variable](https://i.ytimg.com/vi/tmgWKYBYf-o/maxresdefault.jpg)

## Data types
Java is known as a typed language, which means that it forces us to inform the type of a variable when declaring it. We have some types that can be used to apply to variables:
- byte: stores whole numbers from -128 to 127;
- short: stores whole numbers from -32,768 to 32,767;
- int: store whole numbers from -2,147,483,648 to 2,147,483,647;
- long: tores whole numbers from -9,223,372,036,854,775,808 straight to 9,223,372,036,854,775,807;
- float: stores fractional numbers from 6 to 7 decimal digts;
- double: also stores fractional numbers but with a bigger range. From 10 to 15 decimal digits;
- boolean: stores only two values: true or false;
- char: stores a single character.
Once declared, it is not possible to change the type of a variable, we have to perform the operarions related to that type.
All the above are primitive data. We also have the non-primitive data, that are called objects, but it's a advanced matter.

![types](https://lh3.googleusercontent.com/proxy/gZbSNTkU_soHdtrGWnumsPz8s9_78LYp5pKsduP3AjEM-gUmdv6_bhWg3DyWj5aAbuMdk6GUnfUjVQ0xzqmgYgsqGqQ-IZmH3RU_6ooKAGlmR56RwZs)
