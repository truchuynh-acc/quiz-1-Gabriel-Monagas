[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Gabriel Monagas
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer:

#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    int year;
    str color;
public:
    str get_model() {
        return model;
}
    int get_year() {
        return year;
}
    str get_color() {
        return color;
}
    void set_model (str m) {
        model = m;
}
    void set_year (int y) {
        year = y;
}
    void set_color (str c) {
        color = c;
}    

    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;


    myCar.displayDetails();

    return 0;
}

```
