# 🚀 Seru-Seruan Belajar Java! 🎉

Hai, teman-teman! Selamat datang di dunia pemrograman Java! 😃 Di sini kita bakal belajar bareng mulai dari variabel, cara ngasih input, operator logika, sampai operator matematika! Yuk, langsung aja kita mulai! 🚀

Java is EASYYYY kuyyyy wahahahahahah

Tapi Boong wahahhahahaha


## 🎯 Cara Menampilkan Output
Di Java, kita bisa mencetak sesuatu ke layar dengan perintah berikut:

```java
System.out.println("Halo, Dunia!"); // dengan enter
System.out.print("Halo, Java!"); // tanpa enter
```

Contoh penerapannya:

```java
public class JavaSeru {
  public static void main(String[] args) {
    System.out.println("I Love Java!");
  }
}
```
NOTED: nama projek **JavaSeru**
Hasilnya:
```
I Love Java!
```

---

## 🔹 Variabel: Tempat Nyimpen Data!

Variabel itu kayak kotak harta karun yang nyimpen sesuatu yang berharga. 💖✨ Setiap variabel punya tipe data, kayak hati yang cuma bisa diisi perasaan tertentu. Misalnya string, integer, boolean, double, char, dll.

Contohnya:

```java
//tipe_data nama_data = nilai_data
int angka = 2;
String nama = "Andre Firmansyah";
```

Contoh penggunaannya:
```java
public class JavaSeru {
  public static void main(String[] args) {
    int angka = 2;
    System.out.println("Angkaku: " + angka);
  }
}
```
Hasil:
```
Angkaku: 2
```

---

## 📝 Memberi Inputan (Biar Lebih Interaktif!)

Kita butuh bantuan Scanner untuk menerima input dari user! Jangan lupa import dulu:
```java
import java.util.Scanner;
```

Contohnya:
```java
import java.util.Scanner;

public class JavaSeru {
  public static void main(String[] args) {
    Scanner input = new Scanner(System.in);
    
    System.out.print("Masukkan nama: ");
    String nama = input.nextLine();
    System.out.println("Halo, " + nama + "!");

    System.out.print("Masukkan angka favorit: ");
    int angka = input.nextInt();
    System.out.println("Angka favoritmu adalah " + angka);
  }
}
```

Contoh input dan output:
```
Masukkan nama: Andre
Halo, Andre!
Masukkan angka favorit: 7
Angka favoritmu adalah 7
```

---

## 🤔 Operator Logika: Buat Ngambil Keputusan!

Tabel operator logika di Java:

| Operator | Simbol | Keterangan |
|----------|--------|------------|
| AND      | &&  | True jika kedua kondisi true |
| NOT      | !    | Kebalikan nilai boolean |
| >        | >    | Lebih dari |
| <        | <    | Kurang dari |
| >=       | >=   | Lebih dari atau sama |
| <=       | <=   | Kurang dari atau sama |
 
 OR disimbolkan "||" dan  True jika salah satu true 
Contoh penggunaannya:
```java
public class JavaSeru {
  public static void main(String[] args) {
    boolean a = true;
    boolean b = false;
    
    System.out.println("AND: " + (a && b)); // false
    System.out.println("OR: " + (a || b)); // true
    System.out.println("NOT A: " + (!a)); // false
  }
}
```

Hasil:
```
AND: false
OR: true
NOT A: false
```

---

## ➕ Operator Matematika: Hitung-Hitungan Jadi Gampang! 🧮

Berikut adalah beberapa operator matematika yang sering dipakai:

| Operator | Simbol | Keterangan |
|----------|--------|------------|
| Penjumlahan | `+` | Tambah angka |
| Pengurangan | `-` | Kurangi angka |
| Perkalian | `*` | Kali angka |
| Pembagian | `/` | Bagi angka |
| Modulus | `%` | Sisa pembagian |
| Increment | `++` | Tambah 1 unit |
| Decrement | `--` | Kurangi 1 unit |

Contoh penggunaannya:
```java
public class JavaSeru {
    public static void main(String[] args) {
        int a = 10, b = 5;
        
        System.out.println("Penjumlahan: " + (a + b)); // 15
        System.out.println("Pengurangan: " + (a - b)); // 5
        System.out.println("Perkalian: " + (a * b)); // 50
        System.out.println("Pembagian: " + (a / b)); // 2
        System.out.println("Modulus: " + (a % b)); // 0
    }
}
```

Hasil:
```
Penjumlahan: 15
Pengurangan: 5
Perkalian: 50
Pembagian: 2
Modulus: 0
```

---

## 🎉 Kesimpulan
Gimana? Seru kan belajar Java? 😆
Kita udah bahas:

✅ Cara menampilkan output

✅ Variabel dan input dari user

✅ Operator logika buat pengambilan keputusan

✅ Operator matematika buat perhitungan

Ayo terus latihan dan eksplorasi biar makin jago! 🔥 Happy coding! 🚀

