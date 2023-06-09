# ÖDEV : 
* Kullanıcının girdiği sayının basamak değerlerinin toplamını ekrana yazdıran program
```
package DongulerPratik;

import java.util.Scanner;

public class BasamakDegeriHesaplama {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        System.out.print("Bir Sayı Giriniz : ");
        int number=input.nextInt();
        int tempNumber=number;
        int basValue;
        int result=0;
        while (tempNumber!=0){
            basValue=0;
            basValue=tempNumber%10;
            result+=basValue;
            tempNumber/=10;
        }
        System.out.print(number+" Sayısının Basamak Değerlerinin Toplamı : "+result);
    }
}
```
# PATİKA PROFİLİM :
<a href='https://academy.patika.dev/tr/profile'><u>Patika Profilim</u></a>