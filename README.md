# SUMMATIVE-CODE-2
```
#include <iostream>
#include <string>
using namespace std;
int main()
{
    string fullname;
    cout << "Please enter your full name: " << endl;
    getline(cin, fullname);
    {
        int x, y = 1;
        cout << "Please enter a number to factor: " << endl;
        cin >> x;
        while (cin.fail() || x <= 0)
        {
            cout << "Invalid input of number please try again." << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> x;
        }
        for (int z = 1; z <= x; z++)
            y = y * z;

        int w = 50, s = 0;
        cout << "Table from 50-40 " << endl;
        while (s <= 40)
        {
            cout << s << " x " << w << " = " << s * w << endl;
            s++;
        }

        int number = 2;
        int a = 1;
        int power = 5;
        cout << "\nExponent power from 5-0 (example 2^5 - 2^0)" << endl;
        for (int i = 1; i <= power; i++) 
        {
            a = a * number;

            cout << number << "^x" << " = " << a << endl;
            a++;
        }

        cout << "\nFactorial: " << x << " = " << y << endl << "\n" << fullname << ", Thank you! Your results are above." << endl; }
}
```

# I WILL BE PRACTICING THIS CODE FURTHER AT HOME (NOT FEELING WEL SRRY)
