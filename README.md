package com.mycompany.car;

public class Car {
    // Fields (State) - Each car object will have its own color and maxSpeed
    private String color;
    private int maxSpeed;

    // Constructor to initialize the Car object
    public Car(String color, int maxSpeed) {
        this.color = color;
        this.maxSpeed = maxSpeed;
    }

    // Method to display the attributes of the car (Behavior)
    public void displayFeatures() {
        System.out.println("Car color: " + color + ", Max Speed: " + maxSpeed);
    }

    // Main method to create and manage car objects
    public static void main(String[] args) {
        // Creating objects from Car class
        Car car1 = new Car("Red", 150);
        Car car2 = new Car("Blue", 180);
        
        // Displaying features of each object
        car1.displayFeatures(); // Displays: Car color: Red, Max Speed: 150
        car2.displayFeatures(); // Displays: Car color: Blue, Max Speed: 180

        // Note: car1 and car2 are different objects with their own states
    }
}
