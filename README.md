# vcpp-string-popback
This repository contains a simple C++ program demonstrating the use of the string::pop_back() function. The program removes the last character from a string and prints the modified result. It is a beginner-friendly example to understand basic C++ string manipulation using the Standard Template Library (STL).
# 📌 C++ String pop_back() Example

This project demonstrates how to use the **`pop_back()`** function in C++ to remove the last character from a string.

---

## 🧠 Concept Used

- `std::string`
- `pop_back()` function
- Basic input/output using `cout`

---

## 🛠️ Program Code

```cpp
#include <iostream>
using namespace std;

int main() {
    string s = "ranjith";
    s.pop_back();
    cout << s << endl;
    return 0;
}
