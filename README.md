# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance.


## Algorithm:

step 1: Create a base class.

Step 2: Create two child class.

step 3: Create a constructor in the base class and print a message.

step 4: create a function in child class to print a message.


## Program:

Name: Leann Joby Mathew

Reg no: 212222230074

```python
using System;
namespace inheri
{
    public class tyre
    {
        public virtual void display()
        {
            Console.Write("Tyre has been inserted:");
        }
    }
    class Scooter : tyre
    {
        public override void display()
        {
            base.display(); 
            Console.WriteLine("scooter ");
        }
    }
    class Car : tyre
    {
        public override void display()
        {
            base.display();
            Console.WriteLine("car ");
        }
    }
    class program
    {
        static void Main()
        {
            Scooter s = new Scooter();
            s.display();
            Car c = new Car();
            c.display();
        }
    }
}

```

## Output:
![image](https://github.com/Leann4468/Inheritance/assets/121165979/3d495087-782a-4fa2-9079-6f998646ba31)



## Result:
Thus C# program to print some messages using hierarchical inheritance is written and executed sucessfully.
