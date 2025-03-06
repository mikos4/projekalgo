#include <iostream>
using namespace std;

struct kendaraan
{
    int noplat;
    string jenis;
    string merk;
    string model;
    string nama;
    int tahun;
} kdrn[100];

void inputdata();
void tampildata();
void searching();
void bubblesort();

int main()
{
int pilihan;


do
{
 cout << "\n ====== MENU ======\n";
cout << "1. input data\n";
cout << "2. tampilkan data\n";
cout << "3. sorting\n";
cout << "4. close\n";
cout << "menu yang dipilih: ";
cin >> pilihan;

switch (pilihan)
{
case 1:
    inputdata();
break;
case 2:
    tampildata();
break;
case 3:
     bubblesort();
default : cout << "tidak valid";

}
} while (pilihan != 4);
    return 0;
}
int jumlah;
int tambah;
void inputdata(){
    cout << "\njumlah kendaraan yang akan didata: "; cin >> tambah;
    for (int i = jumlah; i < jumlah+tambah; i++)
    {
    cout << "plat nomor kendaraan " << i+1 <<": "; cin >> kdrn[i].noplat;
    cout << "jenis kendaraan " << i+1 <<": "; cin>> kdrn[i].jenis;
    cout << "merk kendaraan " << i+1 << ": "; cin >> kdrn[i].merk;
    cout << "model kendaraan " << i+1 << ": "; cin >> kdrn[i].model;
    cout << "nama pemilik kendaraan " << i+1 << ": "; cin >> kdrn[i].nama;
    cout << "tahun produksi kendaraan " << i+1 << ": "; cin >> kdrn[i].tahun;
    }   
    jumlah+=tambah; 
    return;
}

void tampildata(){
    if (jumlah==0)
    {
        cout << "\ndata kosong";
    }
    
    cout << "\n=== data ===\n";
    for (int i = 0; i <= jumlah; i++)
    {
    cout << "plat nomor kendaraan"<< i+1 << kdrn[i].noplat
        << "jenis kendaraan" << i+1 << kdrn[i].jenis
        << "merk kendaraan" << i+1 << kdrn[i].merk
        << "model kendaraan" << i+1 << kdrn[i].model
        << "nama pemilik kendaraan" << i+1 << kdrn[i].nama
        << "tahun produksi kendaraan" << i+1 << kdrn[i].tahun << endl;
    }
    
}


void bubblesort(){ 
    for (int i = 0; i < jumlah - 1; i++)
    {
        for (int j = 0; j < jumlah - i - 1; j++)
        {
            if (kdrn[j].tahun > kdrn[j+1].tahun)
            {
                swap(kdrn[j], kdrn[j+1]);
            }
            
        }
        
    }
    
}
