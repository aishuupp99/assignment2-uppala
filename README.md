# assignment2-uppala
# ashwini uppala
###### goa is my fav place
**Goa** having lot of **beaches** and cool climate.
* * *
## From maryville to kansas airport travel directions:
1. take flight
    1. chicago
    2. Delhi
    3. Goa
2. Take cabs
    1. From Goa international airport take cab to baga beach.
## Items to be brought to favourite location for maximum enjoyment
- beachware
- hat
- waterbottle
- whisky

[Aishu](AboutMe.md)

*** food Information ***

**food reco** that I would recommend others
|food/drink item| Location| money to pay |
| --- | --- | ---:|
|Biryani | Shah ghouse | 200 |
|Gulab Jamun | MTR | 30 |
|Khalakand | Hyderabad | 75 |
|Mutton Biryani | Bawarchi | 120 |

***Favorite Quotations***
 
# Inspiring Quotations
>**Everyday** is a new chance for **starting over** <br>
>The best **preparation** for tomorrow is doing your **best today**.
*H. Jackson Brown, Jr.*

***Geometry elementary***

# Algorithm to find area of simple polygon

>To find the area of a regular polygon, all you have to do is follow this simple formula: area = 1/2 x perimeter x apothem.
[Link source](https://www.google.com/search?q=area+of+simple+polygon&rlz=1C1GCEA_enUS967US968&oq=area+of+simple+pol&aqs=chrome.0.0i512j69i57j0i22i30l2j0i390l2j69i60.5802j1j7&sourceid=chrome&ie=UTF-8)

import java.util.Scanner;

public class Exercise35 {
    
  public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print("Input the number of sides on the polygon: ");
        int ns = input.nextInt();
        System.out.print("Input the length of one of the sides: ");
        double side = input.nextDouble();
        System.out.print("The area is: " + polygonArea(ns, side)+"\n");
    }
    public static double polygonArea(int ns, double side) {
        return (ns * (side * side)) / (4.0 * Math.tan((Math.PI / ns)));
    }
}
[code source](https://www.w3resource.com/java-exercises/basic/java-basic-exercise-35.php)


