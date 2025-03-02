# Integer-Pointer-Program

Here is the source code for the Integer-Poniter-Program:

#include <iostream>
using namespace std;

int main() {
    // Step 2: Declare three integer variables
    int num1, num2, num3;

    // Step 3: Prompt the user for input
    cout << "Enter three integer values: ";
    cin >> num1 >> num2 >> num3;

    // Step 5: Create integer pointers
    int* ptr1 = new int; // Allocate memory
    int* ptr2 = new int; // Allocate memory
    int* ptr3 = new int; // Allocate memory

    // Step 7: Assign values to the pointers
    *ptr1 = num1;
    *ptr2 = num2;
    *ptr3 = num3;

    // Step 8: Display the values using the pointers
    cout << "The values are: " << *ptr1 << ", " << *ptr2 << ", " << *ptr3 << endl;

    // Step 9: Deallocate the memory
    delete ptr1;
    delete ptr2;
    delete ptr3;

    // Step 10: End
    return 0;
}


