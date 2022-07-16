# KitleIndeks
### Java-101 Vücut Kitle Indeks Hesaplama
  (www.patika.dev)
  
import java.util.Scanner;

public class KitleIndeks {
    public static void main(String[] args) {

        double kilo, boy,indeks;


        Scanner girdi=new Scanner(System.in);

        System.out.print("Lütfen Kilonuzu Giriniz: ");
        kilo = girdi.nextDouble();

        System.out.print("Lütfen Boyunuzu Metre Olarak Giriniz: ");
        boy = girdi.nextDouble();

        indeks = kilo/(boy*boy);
        System.out.println("VÜcut Kitle İndeksiniz: "+indeks);



    }
    }

