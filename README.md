# Garbage Collection

``` java
public class Test{
    void test(){
        MyClass obj = new MyClass();
        obj.name = "jake";
        // 1
    }
}

// in file MyClass.java
public class MyClass{
    int value;
    String name;
}

```

## Question

What could be inserted at // 1, which will make the object referred to by obj eligible for *Garbage Collection*?

## My Understanding

An object is avalaible for *Garbage Collection* when the referrence is assigned to null, meaning the referrence is not used.

* Why the question challenge you?
    * The question was tricky for because I didnt know much about garbage collection and it appeared almost all exams that I have written. So decided to study the *Garbage Collection* so that I can understand what is it and how it works.
    
* What did you learn from the qustion?
    * I have learned when can *Garbage Collection* be available.
    
* Which other concept are related to this question?
    * Memory Management
