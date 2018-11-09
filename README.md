# password-keeper

Henry O'Connor, Bernard Heres, John Diggins
04 / 13 / 2017

Simple password manager application written for my Java I class with two other students.

Create a login screen, allow user to register new account

Verify Password
* 8 to 10 alphanumeric characters, 1 capital letter, 1 number
* 1 special character, NO spaces

Once logged in, user can:
* add new site login info (site, login, password, notes)
* list all site login info
* search for a login based on site

Required Classes & Methods:
* Abstract Password Class - contains print method for passwords and
         validation interface
* Simple Password Class - allows for unvalidated passwords
* Complex Password Class - has validation method that throws exception
* Site class that includes website, username, password, and notes
  * should validate website URL and throw exception if invalid
* A method to save usernames and passwords for Password Keeper
* A method to save Site class data as text
  
This project demonstrates:
* Objects & Classes
* Arrays
* Inheritance
* Polymorphism
* JavaFX
* Exception Handling
* Text I/O
* Abstract classes
* Interfaces
