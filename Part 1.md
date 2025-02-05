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
# Operator logika
Di bawah ini merupakan operator logika yang harus kalian ingat:

**1. AND ==> &&**

**2. OR ==> ||**

**3. NOT ==> !**

**4. Lebih dari ==> >**

**5. Kurang dari ==> <**

**6. Lebih dari atau sama dengan ==> >=**

**7. Kurang dari atau sama dengan ==> <=**




