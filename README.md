class Dog 
{
    // attributes of the dog
	
	int age;
    String name;
    String breed;
    
    Dog(String n, String b, int a) 
    {
        this.name = n;
        this.breed = b;
        this.age = a;
    }

    // Display the dog's detail
    
    void displayInfo() 
    {
        System.out.println("Dog: " + name + " is a " + age + " year old " + breed);
    }
}

public class Main
{
    public static void main(String[] args) 
    {
        // Creating objects from Dog class ("Name", "Breed", Age)
// To add more objects copy and paste the edit: Dog d3 = new Dog("Izzy", "Shih tzu", 5)
    	
        Dog d1 = new Dog("Sugar", "Australian Shepherd", 8);
        Dog d2 = new Dog("Sandy", "Beagle", 7);
        Dog d3 = new Dog("Izzy", "Shih tzu", 5);
        
        // Calling methods on objects
        
        d1.displayInfo();
        d2.displayInfo();
        d3.displayInfo();
    }
}
 
