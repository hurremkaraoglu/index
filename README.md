# index

import java.util.Scanner;

public class VucutKitleIndeksiHesaplayanProgram {
    public static void main(String[] args) {
        double boy, kilo, indeks;

        Scanner input = new Scanner(System.in);
        System.out.print("Lütfen boyunuzu giriniz : ");
        boy= input.nextDouble();

        Scanner input2 = new Scanner(System.in);
        System.out.print("Lütfen kilonuzu giriniz : ");
        kilo= input2.nextDouble();

       

        indeks = kilo / (boy * boy) ;
        System.out.println("Vücut Kitle İndeksiniz : " + indeks);

    }
}
