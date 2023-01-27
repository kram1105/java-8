# java-8
This repo contains java 8 code examples from the course on Udemy - https://www.udemy.com/course/java-8-new-features-in-simple-way/

Lambda Expression - It is an anonymous function not having name, not having modifiers, not having any return type. We can convert method into lambda expression by removing name, modifiers and return type.
For example:
public void m1() {
    System.out.println("Hello");
}

can be written as 

() -> { System.out.println("Hello"); }

Similarly other example

public int getLength(String s) {
    return s.length();
}

can be written as 

(String s) -> { return s.length(); }