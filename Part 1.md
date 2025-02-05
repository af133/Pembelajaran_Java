# Varibel, Memberi inputan, Operator Logika, dan Operator Matematika

Untuk menampilkan nilainya sintasknya sebagai berikut:
```
System.out.println(); 
```
atau
```
Systm.out.print();
```
Penerapannya:
```
public class JavaApplication1 //nama projek JavaApplication1 
{
  public static void main (String [] args)
  {
    System.outprintln("I Love You")
  }
}
```
Hasil:
```
I Love You
```
# # Varibel
tipe_data nama_variable = nilai variable;

Contoh:
```
int angka = 2;
String nama = "Andre Firmansyah";
```
Penerapannya:
```
public class JavaApplication1 //nama projek JavaApplication1 
{
  public static void main (String [] args)
  {
    int angka = 2;
    System.out.println(angka);
  }
}
```
Hasil:
```
2
```
# # Memberi inputan
Kita harus mengimport sebuah method yaitu ```import java.util.Scanner```
Penerapan:
```
import java.util.Scanner
public class JavaApplication1 //nama projek JavaApplication1 
{
  public static void main (String [] args)
  {
    Scanner input = new Scanner(System.in);
    String nama = input.nextLine();
    System.out.println("Nama anda: " + nama)

    int angka = input.nextint();
    System.out.println("Angka: " + angka);
  }
}
```
Hasil:
```
Andre Firmansyah // memberikan inputan Andre Firmansyah
Nama anda: Andre Firmansyah
2 // memberikan inputan 2
Angka: 2
```
# # Operator logika
Di bawah ini merupakan operator logika yang harus kalian ingat:

**1. AND ==> &&**

**2. OR ==> ||**

**3. NOT ==> !**

**4. Lebih dari ==> >**

**5. Kurang dari ==> <**

**6. Lebih dari atau sama dengan ==> >=**

**7. Kurang dari atau sama dengan ==> <=**

| Operator | Simbol | Keterangan |
|----------|--------|------------|
| AND      | `&&`   | True jika kedua kondisi bernilai True |
| OR       | `||`   | True jika salah satu kondisi bernilai True |
| NOT      | `!`    | Membalikkan nilai boolean |
| Lebih dari | `>`  | True jika nilai kiri lebih besar dari kanan |
| Kurang dari | `<` | True jika nilai kiri lebih kecil dari kanan |
| Lebih dari atau sama dengan | `>=` | True jika nilai kiri lebih besar atau sama dengan kanan |
| Kurang dari atau sama dengan | `<=` | True jika nilai kiri lebih kecil atau sama dengan kanan |
Penerapannya:
```
public class JavaApplication1
{
  public static main (String [] args)
  {
    boolean a = true;
    boolean b = false;
  
    // AND (&&)
    System.out.println("AND: " + (a && b)); // false
  
    // OR (||)
    System.out.println("OR: " + (a || b)); // true
  
    // NOT (!)
    System.out.println("NOT A: " + (!a)); // false
    System.out.println("NOT B: " + (!b)); // true

    // Operator Perbandingan
    int x = 10, y = 5;
    System.out.println("x > y: " + (x > y));  // true
    System.out.println("x < y: " + (x < y));  // false
    System.out.println("x >= y: " + (x >= y)); // true
    System.out.println("x <= y: " + (x <= y)); // false
  }
}
```

