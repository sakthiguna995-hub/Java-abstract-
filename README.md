# Java-abstract-
package gunasakthiR;

abstract class vehicle{
 
 public abstract void start();

 public void speed() {
     System.out.println("The speed increases.");
 }
}

class car extends vehicle {
 
 public void start() {
     System.out.println("the car starts.");
 }
}

class bike extends vehicle {
 
 public void start() {
     System.out.println("the bike starts");
 }
}

public class Abstract {
 public static void main(String[] args) {
     vehicle car = new car ();
     car.start();  
     car.speed();        
     vehicle bike = new bike();
     bike.start();  
     bike.speed();        
 }
}
