# lecture--10---cipher-schools

In this lecture i learned about loops part 2 and about pre increment and post increment and here is an basic example code of pre increment and post increment 


#include <iostream>

int main() {
    int a = 0, b = 0;

    for (int i = 0; i < 10; ++i) {
        std::cout << "Iteration " << i + 1 << ": ";
        std::cout << "a = " << ++a << ", "; 
        std::cout << "b = " << b++ << std::endl; 
    }

    std::cout << "Final values - a: " << a << ", b: " << b << std::endl;

    return 0;
}
