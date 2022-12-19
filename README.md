# Galang-Dwiwana-Thabrani IF-B
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemrogaman
<br> Nama		: Galang Dwiwana Thabrani
<br>NIM		:	1227050048
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 


## Deskripsi Umum
PROGAM MENENTUKAN MATRIKS TRANSPOSE
## Source Code

```
#include <iostream>
#include <iomanip> 
using namespace std;
 
int main()
{
  int matriks[100][100];
  int kolom, baris, a, b;
  
  cout<< "NAMA : GALANG DWIWANA THABRANI"<<endl;
  cout<< "NIM  : 1227050048"<<endl;
  cout<< "================================" << endl;
  cout<< "#PROGAM MENGHIUTUNG TRANPOSE MATRIKS#" << endl;
  cout<< "================================" << endl;
 
  cout<<"Input jumlah baris : ";
  cin>>baris;
 
  cout<<"Input jumlah kolom : ";
  cin>>kolom;
  cout<<endl;
 
  // proses input array
  for(a = 0; a < baris ; a++){
    for(b = 0; b < kolom; b++){
      cout << "Baris ke " <<a+1<<", kolom ke "<<b+1<< " : ";
      cin >> matriks[a][b];
    }
    cout << endl;
  }
 
  cout << "Hasil matriks: " << endl;
  // menampilkan array
  for(a = 0; a < kolom ; a++){
    for(b = 0; b < baris ; b++){
      cout <<setw(3) <<matriks[b][a] << " ";
    }
    cout << endl;
  }
  
  cout<<"===================================" << endl;
  cout<<"hasil matriks setelah di transpose"<<endl;
  //menampilkan matriks transpose
  for (a = 0; a < baris; a++) {
  	for (b = 0; b < kolom; b++) {
  		cout << " " << matriks[a][b];
	  }
	  cout << endl;
  }
  return 0;
}
```

## Output
