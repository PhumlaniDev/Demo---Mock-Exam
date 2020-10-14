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

What could be inserted at // 1, which will make the object referred to by obj eligible for Garbage Collection?

## My Understanding

An object is avalaible for garbage collection when the referrence is assigned to null, meaning the referrence is not used.

* Why the question challenge you?
