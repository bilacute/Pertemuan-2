#include <iostream>
using namespace std;

string nama, nim;
int usia;

int main()
{
    cout << "Masukkan nama: ";
    cin >> nama;

    cout << "Masukkan NIM: ";
    cin >> nim;

    cout << "Masukkan usia: ";
    cin >> usia;

    cout << "Nama: " << nama << endl;
    cout << "NIM: " << nim << endl;
    cout << "Usia: " << usia << endl;

    int i = 0;
    do {
        cout << nama <<endl;
        i++;
    }
    while (1 < 20);

    return 0;
}
