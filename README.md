# tugas.cpp
tugas

saya ingin ebeli sepatu senayak 15 kali
#include <iostream>
using namespace std;

int main() {
    // Perulangan untuk mencetak "saya imgin ebeli sepatu" sebanyak 7 kali
    for (int i = 1; i <= 15; i++) {
        cout << "saya ingin ebeli sepatu" << endl;
    }

    return 0;
}


Menampilkan deret bilangan kelipatan 6, yang batas awal dan akhirnya diinputkan oleh user!
#include <iostream>
using namespace std;

int main() {
    int awal, akhir;

    // Input dari user untuk batas awal dan akhir
    cout << "Masukkan batas awal: ";
    cin >> awal;
    cout << "Masukkan batas akhir: ";
    cin >> akhir;

    // Menampilkan bilangan kelipatan 6 dari batas awal sampai akhir
    cout << "Bilangan kelipatan 6 antara " << awal << " dan " << akhir << " adalah: " << endl;

    // Mulai dari batas awal atau bilangan kelipatan 6 pertama di atas batas awal
    if (awal % 6 != 0) {
        awal = (awal / 6 + 1) * 6; // Menyesuaikan agar dimulai dari kelipatan 6
    }

    // Perulangan menampilkan kelipatan 6
    for (int i = awal; i <= akhir; i += 6) {
        cout << i << " ";
    }

    cout << endl;
    return 0;
}



ika memiliki 7 toples permen, dengan jumlah yang berbeda-beda. Mika ingin menghitung berapa total permen yang dia miliki. Buatlah program yang meminta mika memasukkan jumlah permen di setiap toples dan menghitung jumlah permen yang ada!
#include <iostream>
using namespace std;

int main() {
    int awal, akhir;

    // Input dari user untuk batas awal dan akhir
    cout << "Masukkan batas awal: ";
    cin >> awal;
    cout << "Masukkan batas akhir: ";
    cin >> akhir;

    // Menampilkan bilangan kelipatan 6 dari batas awal sampai akhir
    cout << "Bilangan kelipatan 6 antara " << awal << " dan " << akhir << " adalah: " << endl;

    // Mulai dari batas awal atau bilangan kelipatan 6 pertama di atas batas awal
    if (awal % 6 != 0) {
        awal = (awal / 6 + 1) * 6; // Menyesuaikan agar dimulai dari kelipatan 6
    }

    // Perulangan menampilkan kelipatan 6
    for (int i = awal; i <= akhir; i += 6) {
        cout << i << " ";
    }

    cout << endl;
    return 0;
}
