public class Dog {
    // Instance variables
    private String name;
    private String color;

    // Parameterized constructor
    public Dog(String name, String color) {
        this.name = name;
        this.color = color;
    }

    // Method to display dog details
    public void displayDetails() {
        System.out.println("Dog's Name: " + name);
        System.out.println("Dog's Color: " + color);
    }

    // Main method to test the class
    public static void main(String[] args) {
        // Creating a Dog object using the parameterized constructor
        Dog myDog = new Dog("Buddy", "Brown");

        // Printing the values of the variables
        myDog.displayDetails();
    }
}
