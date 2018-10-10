# Singtel

class Animal
{
    void walk()
    {
        System.out.println("I am walking"):
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
        void soundChiken()
        {
         System.out.println("A chicken says cluck cluck");
        }
        
 }
 class Duck extends Animal
 {
        void soundDuck()
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
        void soundChicken()
        {
        System.out.println("Rooster says Cock-a-doodle-doo");  
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
 
 
 
