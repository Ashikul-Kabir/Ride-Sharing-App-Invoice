# Ride-Sharing-App-Invoice
I used the concepts of OOP(Object Oriented Programming) in C++ to write my
program. This program shows the breakdown of fares in detail for “McB ride sharing
system”. Here I will discuss the things I’ve implemented throughout my program:

1. First, I created a parent class named Vehicle where I declared the common
variables to be used throughout the vehicle categories. Then I declared member
function of three types to describe whether the vehicle is a car, motorcycle or
bicycle. I intended to use the concept of multilevel inheritance.
2. Then I created a subclass Car which is derived from Vehicle class inheriting the
attributes of Vehicle. I declared the relevant variables & functions to determine
the breakdown of fares for a car. I created a parameterized constructor to pass the
user input of variables to the Car class so that it can be initialized as soon as
object of the car is created. Then I declared getFare() function to apply all the
conditions for a car & passed promoCode as a value to the function as mentioned
in task 1. To show the output of the calculations in console, I declared another
function displayFare() by passing paymentMethod as a value.
3. Motorcycle & Bicycle classes were derived in the same way from Vehicle class.
The functions of the classes used were also similar. Only difference here is in the
assigned values of the respective classes as per task 1.
4. Distance, speed, promo codes etc. were applied in the calculation as per the
instructions given.
5. The main() function begins with a user guide or menu. I used a recurring menu
for the ease of displaying the input & output units in console. I created the objects
of the classes of vehicles & called all the required functions using the objects to
display the desired output. This function is basically used to execute the whole
program as per user input & display the invoice of fares for a user.
6. Finally, I tried to keep the code very clean, accurate & specific in terms of instructions
& logics. It should work properly for every possible condition that a user might
want to implement while using any identical ride sharing app.
