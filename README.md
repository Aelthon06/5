# 5
#include <iostream>
#include <string>
using namespace std;

int main() {

    string courses[] = { "BSU CC", "BSU BA", "HNC CC", "HND" };

    for (int i = 0; i < 4; i++) {
        cout << courses[i] << endl;
    }

    for (auto course : courses) {//range based for loop
        cout << course << endl;
    }

    char letters[] = { 'C', 'o', 'd', 'e', 'L', 'a', 'b'};
    for (auto letter : letters) {
        cout << letter;
    }
}
