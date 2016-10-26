# Java-PowerPoint
Java
What is it?
Java is a programming language
     Java 		   vs	   JavaScript

Java Coding

Common words you’ll see
Public: Tells java interpreter, THIS should be available to all other classes.

Class: A “blueprint” for what you want the program to do.

Static: Only a class can call for this function to execute.

Void: This function wont return any values after it is done executing.

Main: This is required in all classes.

(String[ ] args): A parameter used commonly. When used in the MAIN function, it would mean every MAIN function must accept an array of string objects

System.out: object that outputs info in diff ways

Println: Function in system out that prints and sets a new line at the end of the print.

Java Coding Review

```java
public class HelloWorld
{
   public status void main(String[] args){
	System.out.printIn(“Hello World”);
	char j = ‘j’;
	}
}
```

Cool Extras 		Java’s History
In 1990 Sun Microsystems started a program to make software that would be used in consumer electronics. They called this program “Green”. A developer named James Arthur Gosling began writing software in C++ for embedding() into various systems like VCR’s, Toasters, Microwave Ovens, and PDA’s. When writing software for these technologies, Gosling’s team found that C++ had emphasis on speed, not reliability. In 1991, After working together to try to create a more reliable system, they came up with a new programming language called “Oak”. With this language, they developed impressive new devices where you did not need buttons or a keyboard to operate them, only a tiny screen, somehow, this technology did not take off. Thanks to an idea from Billy Joy, one of the co-founders of Sun Microsystems, they decided to release Java for free over the internet and it later became a standard. Oak was later renamed to Java, due to advice from some trademark lawyers that ruled out “Oak” as a possibility.

Cool Extras 			Research
Links
https://www.sitepoint.com/beginning-java-data-types-variables-and-arrays/ (Article w/ info on a ton of Java basics( DataTypes, intro, history))
http://lifehacker.com/5988800/what-is-java-is-it-insecure-and-should-i-use-it (Short article, explains what java runtime is & compares it to JS)
http://stackoverflow.com/questions/3265357/compiled-vs-interpreted-languages (Stack overflow question about Compiled vs Interpreted code)
https://www.youtube.com/playlist?list=PLFE2CE09D83EE3E28 (How to use Java YouTube Playlist)
https://www.java.com/en/download/faq/java_javascript.xml (Java Official website comparison Java vs JS)
https://developer.mozilla.org/en-US/docs/Web/JavaScript/About_JavaScript (JavaScript official MDN site JS vs Java)
https://www.cs.utexas.edu/~scottm/cs307/javacode/codeSamples/LinkedList.java (Java Linked list example + site has basic java examples. )

Here are the notes I used:

Page 1:
At one point, we were all new to working with computers. Three months ago, I couldn’t tell you what a programming language was. I couldn’t even tell the difference between a server, client, or a database was. There are many people that use computers without thinking about how awesome they really are, and how they really work. Java is a programming language that has been used to do lots of amazing things. Before we get into it, I’m just going to say that this is for the most part, a peek, at Java. A lot of the points I’m going to make, will have detailed articles that help define them.


Page 2:
(CONCURRENT) This means It has the ability to run several programs, or several parts of the program in parallel. MULTI-THREADED
(CLASS-BASED) By class-based, it means that each class and each instance is a distinct entity. In Java you define a class with something like this^ ‘click’
(Explain code…) Mention there’ll be a mini code review in a few slides.
Explain BYTE CODE
Explain Java Virtual Machine

Page 3:
Here are some differences between Java and JavaScript. I knew they were different, but I always thought they were very similar to each other. It turns out they are almost completely different, but they have some similar patterns, like most programming languages
To help understand the differences, you need to understand the difference between front-end development and back-end development.
Java is typically a back-end program, Java is compiled into byte code (A virtual machine-friendly interpreted language) before it can be run. The compiler typically lives in the server. Java can also create Java Applets that can be run by the browser.
Key ideas, Think of Java as a programming language, ((NOT a scripting language)), that is compiled first, in the back-end by the server. When JavaScript is, for the most part, a front-end development language. It is run(interpreted, and executed) in the browser(NOTE, Javascript can also be run in the back-end)
The Data types for Java (PRIM: Integer, Character, Boolean, Floating Point NON-PRIM: Classes, Interfaces, Arrays.)
The Data types for JavaScript (6 data types that are primitive: Boolean, Null, Undefined, Number, String, Symbol) It also has am Object data type.

Page 4:
Public: talk about it relating to scope
What is System?.___?.___?
System is a class in the Java.lang package
System has members like .out that are static, or things that can only be called by a class.

COMMON PRACTICE = for creating a constant(const) Use all UPPERCASE

Page 5:
Compare the two sets of code
Remember to talk about:
 the single quote string difference.
The use of let, var, and const
The similarity in patterns.
Dot notation in Java looks common.
BEFORE using variable you must declare it first. TYPE then NAME. or assign as you declare. like with JS.

Page 6:
Here’s a few “cool” extra things I found online in case anyone wants to look into this some more!

Page 7:
I  have a page with some links I found helpful. I added a short comment describing what each article is about & I ordered them from most helpful to least helpful. This is a personal opinion, I even put the documentation from the Java website at the bottom!
