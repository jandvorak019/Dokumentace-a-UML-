# Dokumentace-a-UML-


Simple program that has 2 classes, classOne, classTwo. We use the classTwo inside the classOne to display a message from classTwo.


## 

```java
public class classOne {

    public static void main(String args[]) {

        classTwo classTwoObject = new_classTwoClass();
        classTwoObject.displayMessage();
    }
}
```
The object created in classOne is calling the method from classTwo to print out a message.

## License
Jan Dvořák©
