#include "std_lib_facilities.h"

int main()
{
    int counter{};
    int n{};
    cout << "Enter the number of primes you want me to find starting from 2: ";
    cin >> n;

    cout << "Here are the first " << n << " primes:" << "\n";
    
  
        for (int number = 2; number <= 99999999; ++number) {
            bool isPrime = true;

            for (int i = 2; i * i <= number; ++i) {
                if (number % i == 0) {
                    isPrime = false;
                    break;
                }
            }

            if (isPrime) {
                cout << number << " ";
                counter++;
            }
            if (counter == n) {
                break;
            }
        }
    

    return 0;
}
