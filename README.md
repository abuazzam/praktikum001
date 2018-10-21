# praktikum001

## latihan1.cpp: progam menghitung luas persegi panjang.

### Alur algoritma
1. tentukan variable `int p;`, `int l;` dan `int luas;`
2. input data panjang dari keyboard dengan perintah `cin >> p;`
3. input data lebar dari keyboard dengan perintah `cin >> l;`
4. hitung luas dengan perintah `luas = l * p;`
5. tampilkan hasilnya dengan perintah `cout << luas;`

### code lengkapnya adalah:
```c++

#include<iostream>

using namespace std;

int main() {
    int p, l, luas;
    
    cout << "Masukkan panjang: ";
    cin >> p;
    cout << "Masukkan lebar: ";
    cin >> l;
    
    luas = p * l;
    
    cout << "Luas persegi panjang adalah: " << luas << endl;

    return 0;
}

```

### hasilnya:
![ss_hasil](https://raw.githubusercontent.com/abuazzam/praktikum001/master/ss_latihan1.png)
