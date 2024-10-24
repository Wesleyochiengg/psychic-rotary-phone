#include <iostream>

class Addition {
private:
    int a, b, c;

public:
    Addition() : a(22), b(30), c(50) {}

    void product() {
        std::cout << "The product of the integers is: " << (a * b * c) << std::endl;
    }
};

int main() {
    Addition add;
    add.product();
    return 0;
}
