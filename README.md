# Singtel

class Animal
{
    void walk()
    {
        System.out.println("I am walking"):
     }
     void sound()
     {
     }
 }
 
 class Bird extends Animal
{
    void fly()
    {
        System.out.println("I am Flying"):
     }
     void sing()
     {
      System.out.println("I am Singing"):
     }
 }
 
 class Chicken extends Animal
 {
        void sound()
        {
         System.out.println("A chicken says cluck cluck");
        }
        
 }
 class Duck extends Animal
 {
        void sound()
        {
         System.out.println("A duck says Quack Quack");
        }
        void swim()
        {
          System.out.println("I am swimming");  
        }
 }
 
 class Rooster extends Chicken
 {
        void sound()
        {
        System.out.println("Rooster says Cock-a-doodle-doo");  
        }
 }
 
 class Parrot extends Bird
 {
        void soundParrot(Animal animal)
        {
         if(animal.sound.equals("Dog says woof woof"))
         {
         System.out.println("A parrot living with dogs says woof woof");
         }
         if(animal.sound.equals("Cat says meow"))
         {
         System.out.println("A parrot living with dogs says meow");
         }
         if(animal.sound.equals("Rooster syas Cock-a-doodle-doo"))
         {
         System.out.println("A parrot living with Rooster syas Cock-a-doodle-doo");
         }
        }
 }
 
 
 public class Solution
{
    public static void main(String[] args)
    {
        Bird bird = new Bird();
        bird.walk();
        bird.fly();
        bird.sing();
    }
 }
 
 
 
