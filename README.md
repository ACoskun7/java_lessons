# java_lessons
import java.util.Scanner;
public class HesapMakinasi {
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        System.out.println("Lütfen işlem operatörnü giriniz. işlmeler: *,-,+,/ olarak girmenizi rica ediyoruz.");
        String islem;
        islem=scan.next();
        System.out.println("Lütfen ilk sayiyı giriniz.");
        int a,b;
        a=scan.nextInt();
        System.out.println("Lütfen ikinci sayıyı giriniz.");
        b=scan.nextInt();
        switch (islem){
            case "*":
                System.out.println("işlemin sonucu " +(a*b));
                break;
            case "+":
                System.out.println("işlemin sonucu " +(a+b));
                break;
            case "/":
                System.out.println("işlemin sonucu " +(a/b));
                break;
            case "-":
                System.out.println("işlemin sonucu " +(a-b));
                break;
            default:
                System.out.println("Girdiginiz işlem yanlış veya geçersizdir.");
        }

    }
}
