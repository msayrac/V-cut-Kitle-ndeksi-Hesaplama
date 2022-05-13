# Vucut-Kitle indeksi-Hesaplama
Vücut Kitle İndeksi Hesaplama
Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.

Formül
Kilo (kg) / Boy(m) * Boy(m)

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        double boy, kilo,index;

        System.out.println("Lutfen boyunuzu (metre cinsinde) giriniz :");
        Scanner input_boy = new Scanner(System.in);

        boy = input_boy.nextDouble();

        System.out.println("Lutfen kilonuzu giriniz :");
        Scanner input_kilo = new Scanner(System.in);
        kilo =input_kilo.nextDouble();

        index = (kilo)/(boy*boy);

        System.out.println("Vucut kitle indexsiniz : " + index);
    }
}

