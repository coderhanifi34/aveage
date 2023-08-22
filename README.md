import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int matematik, turkce, fizik, kimya;

        Scanner input = new Scanner(System.in);

        System.out.println("matematik notunuz ;");
        matematik = input.nextInt();

        System.out.println("turkce notunuz");
        turkce = input.nextInt();

        System.out.println("fizik notunuz :");
        fizik = input.nextInt();

        System.out.println("kimya notunuz :");
        kimya = input.nextInt();

        double average = (matematik + turkce + fizik + kimya) / 4;

        if (average > 50) {
            System.out.println( average +"tebrikler üst sınıfa geçtiniz");

        }else  {
            System.out.println( average +"sınıfıta kaldın kaybol.");
        }
    }
}
