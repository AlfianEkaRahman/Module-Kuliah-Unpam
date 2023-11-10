#include <iostream>
using namespace std;

int main() {
    double pinjaman = 10000000.0; 
    double bunga = 0.015;  
    double cicilan_minimal = 1000000.0; 
    int bulan = 0;

    cout << "Bulan\tSisa Hutang" << endl;

    while (pinjaman > cicilan_minimal) {
        bulan++; 
        double bunga_bulanan = pinjaman * bunga; 
        double cicilan = min(cicilan_minimal, pinjaman * 0.1);  
        double sisa_hutang = pinjaman + bunga_bulanan - cicilan;

        cout << bulan << "\t" << sisa_hutang << endl;

        pinjaman = sisa_hutang;
    }

    cout << "Sisa hutang kurang dari 1 juta. Pinjaman selesai." << endl;

    return 0;
}
