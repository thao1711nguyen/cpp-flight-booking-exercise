# cpp-flight-booking-exercise
Review
3 min
Congratulations! We have learned a lot about variable scope and different storage 
classes
Preview: Docs Loading link description
. Let’s revise the concepts that we learned:

Variables
Preview: Docs Loading link description
 follow scope rules in C++:
global scope (declared outside 
functions
Preview: Docs Loading link description
, accessible everywhere)
local scope (within functions/blocks)
Each scope determines where variables can be accessed and modified. Variables in inner blocks can access outer block variables but not vice versa, following the principle of scope nesting. This helps prevent naming conflicts and maintains variable isolation where needed.
Storage classes affect variable behavior:
static variables retain values between function calls and are shared among class 
objects
Preview: Docs Loading link description
.
extern enables variable sharing across 
files
Preview: Docs Loading link description
.
auto lets the compiler deduce variable types automatically.
mutable members can be modified even in read-only functions.
Variables are created when entering their scope and destroyed when leaving it, except for static variables, which maintain their value throughout program execution.
Understanding scope and storage classes is crucial for memory management, code organization, and preventing unintended variable access or modification in C++ programs.

Instructions
Review the code in the editor to see how the concepts we’ve discussed can be used together.

For extra practice, you can do the following:

Booking history tracking: Store and access booking details in inner scopes, ensuring that the user who initiated it can only update each booking.
Booking statistics: Implement a feature to track statistics such as the total number of bookings made, total cancellations, and total revenue generated from all users.

