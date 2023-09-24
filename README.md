# Java

## Preambule

Java is a hight-level, class-based, object-oriented lang. His syntax is similar to C and C++ lang, but has fewer low-level facilitie than them. His runtime provides dynamic capabilities.  
The five primary goals at his creation:
- must be simple, ob-oriented an familiar
- must be robust and secure
- must be portable and architecture-neutral
- must execute hight performance
- must be interpreted, threaded ans dynamic  

All code is written inside a classes and every data item is an object, execpt the primitive data types(int float, bool, char).
Unlike C++, his doesn't support operator overloarding or multiple inheritance for classes but is supported for interfaces

## How to use

Java is an language who need to be compile then:
- Check if you already have Java Compiler installed on your system: `javac --version`  
- If you see an error like “Command 'javac' not found ..." this mean you need to install JDK (Java Development Kit): `sudo apt install default-jdk`  
- Now you can compile: `javac Filename.java` it generate a *.class file names Filename  
- If no error message run with: `java Filename`  

## Syntax

```java
// single line
/* 
    multiple line
*/
/**
 * Print a Hello world sentence in terminal              (1)
 * <p>
 * Longer description. If there were any, it would be    (2)
 * here.
 * <p>
 * And even more explanations to follow in consecutive
 * paragraphs separated by HTML paragraph breaks.
 *
 * @param  variable no argument here.                    (3)
 * @exception classname Describe an execption tha may be thrown from this method 
 * @return in stdin "Hello world!".
 */
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
