# Girilen-Say-lardan-Min-ve-Max-De-erleri-Bulma
Java ile klavyeden girilen N tane sayma sayısından en büyük ve en küçük sayıları bulan ve bu sayıları ekrana yazan programı yazın.

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Kaç tane sayı gireceksiniz :");
        int n = inp.nextInt();
        int as = 0;
        int max = 0, min = 0;

        for (int y = 1; y <= n; y++) {

            System.out.print(y + ". Sayıyı giriniz : ");
            int number = inp.nextInt();

            if (y == 1) {
                max = number;
                min = number;
              
            }


            if (number > max) {
                max = number;
                System.out.println(max);
            }
            if (number < min) {
                min = number;
                System.out.println(min);
            }

        }

        System.out.println("En buyuk sayi: " + max);
        System.out.println("En kucuk sayi: " + min);


      }
    }
https://app.patika.dev/ahmetfurkan




![image](https://user-images.githubusercontent.com/107626332/182335182-0da9b10c-ef4a-419f-a4b3-a945b5d2db01.png)
