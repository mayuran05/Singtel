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
 class butterfly extends Animal 
 {
   
   void fly()
   {
   System.out.prinln("I am Flying");
   }
 }
 
 class Catterpiller extends Butterfly
 {
  vod fly()
  {
   System.out.prinln("We can change their behaviour over time");
  }
 }
 
 class Fish extends Animal
 {
        String colour;
        String size;
        void walk()
        {
        System.out.println("Fish cannot walk");  
        }
        void swim()
        {
        System.out.println("I am swimming");  
        } 
        void habbit()
        {
        System.out.println("Every fish has different habbits")
        }
 }
 
 class Shark extends Fish
 {
        void habbit()
        {
        System.out.println("Shark eats other fish");
        }
 }
 class ClownFish extends Fish
 {
        void habbit()
        {
        System.out.println("Clownfish make jokes");
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
 
 
 
        int nfly=0;
        int nwalk=0;
        int nSing=0;
        int nSwim=0;
 foreach(a:animals)
 {
  
        
 }
 
 
