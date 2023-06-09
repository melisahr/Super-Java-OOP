# Super-Java-OOP
Language: Java

Super is a keyword used to invoke the superclass(parent).


How?
Person class has attributes name and age, while hero has a power attribute.
In the Hero constructor, there's a parameter with values of String name, int age, 
and String power.
For the Hero class to invoke the name and age from the Person class, use the super keyword with arguements of name and age. 
In addition, within the Hero constructor use a this.power. 
The Person construtor has this.name and this.age within and a parameter of 
String name and int age. 

For the Hero2, we have a method of toString(), which return an object from a string.
In the Person class, the toString method returns name and age and a new line.
In the Hero class, the toString method returns the super.toString() and this.power. 
To call, use System.out.println(hero2.toString()).


