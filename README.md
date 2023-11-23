1. Menampilkan Panjang String
#include <iostream>
#include <string>

int main() {
    std::string nama;

    // Meminta input dari pengguna
    std::cout << "Masukkan sebuah nama: ";
    std::cin >> nama;

    // Menampilkan panjang string menggunakan fungsi size() dari string
    std::cout << "Panjang string \"" << nama << "\" adalah " << nama.size() << " karakter." << std::endl;

    return 0;
}


2. Menggabungkan Dua String

#include <iostream>
#include <string>

int main() {
    std::string namaLengkap, gelar;

    // Meminta input dari pengguna
    std::cout << "Masukkan nama lengkap: ";
    std::getline(std::cin >> std::ws, namaLengkap); // Menerima input string dengan spasi

    std::cout << "Masukkan gelar: ";
    std::getline(std::cin >> std::ws, gelar); // Menerima input string dengan spasi

    // Menggabungkan kedua string menggunakan operator +
    std::string gabungan = namaLengkap + " " + gelar;

    // Menampilkan hasil penggabungan
    std::cout << "Hasil penggabungan: " << gabungan << std::endl;

    return 0;
}

