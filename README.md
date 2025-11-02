# level3-task11
#include <iostream>
using namespace std;

int main() {
    for (int i = 1; i <= 10; i++) {
        for (int j = 1; j <= 10; j++) {
            cout << i << " x " << j << " = " << i * j << "\t";
        }
        cout << endl; // hər sətrdən sonra yeni sətir
    }

    return 0;
}
