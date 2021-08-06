1 import java.util.*;
2public class Stage0_DEVIKA_script
3{
          
4static int hammingDist(String SU, String TH)
5{
6    int i = 0, count = 0;
7    while (i < SU.length())
8    {
9        if (SU.charAt(i) != TH.charAt(i))
10            count++;
11       i++;
12    }
13    return count;
14}
 
15public static void main (String[] args)
16{
17    String SU = "@Devika";
18    String TH = "@Devpoo";
19 
20    
21    System.out.println("Devika Kaliana, devikakaliana94@gmail.com,@Devika, Gemonics, @Devpoo, "+ hammingDist (SU, TH));
22    
23}
24}

