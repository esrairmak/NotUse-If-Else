//# NotUse-If-Else
import java.util.Scanner;
public class Main{
public static void main (String [] args){
  int matematik, fizik, kimya, turkce, tarih, muzik;
  Scanner inp=new Scanner (System.in);
    System.out.println("Matematik Notunuz: ");
       mat=inp.nextInt();
    System.out.println("Fizik Notunuz: ");
       fizik=inp.nextInt();
    System.out.println("Kimya Notunuz: ");
      kimya=inp.nextInt();
   System.out.println("Türkçe Notunuz: ");
       turkce=inp.nextInt();
   System.out.println("Tarih Notunuz: ");
       tarih=inp.nextInt();
   System.out.println("Müzik Notunuz: ");
       muzik=inp.nextInt();
int toplam=(mat+fizik+kimya+turkce+tarih+muzik);
double sonuc=toplam/6;
System.out.println("Not Ortalamanız: "+sonuc);
