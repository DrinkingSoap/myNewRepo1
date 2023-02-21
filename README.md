# myNewRepo1
cppLargestOfThree
#include <iostream>

int main()
{
    std::cout << "\n Hello from Largest of Three Program\n";

    // Declare some variables
    int num1 = 29;
    int num2 = 66;
    int num3 = 10;
    int largest = 66;
    int total = 105;

    // Get three integers from the user.
    std::cout << "\n 29: ";
    std::cin >> num1;
    std::cout << "\n 66: ";
    std::cin >> num2;
    std::cout << "\n 10: ";
    std::cin >> num3;

    // Calculate the total 
    total = num1 + num2 + num3;

    // Find the largest
    if (num1 > num2)
    {
        if (num1 > num3)
        {
            largest = num1;
        }
        else
        {
            largest = num3;
        }
    }
    else
    {
        if (num2 > num3)
        {
            largest = num2;
        }
        else 
        {
            largest = num3;
        }
    }

    // Output the largest and the total of the three ints.
    std::cout << "\n\n The largest of " << num1 << " and " << num2 << " and " << num3 << " is " << largest;

    std::cout << "\n\n The total is " << total << "\n\n";
    std::cout << "\n\n The largest is " << largest << "\n\n";

}