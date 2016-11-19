import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner stdin = new Scanner(System.in);
        int n = Integer.parseInt(stdin.nextLine()); // Number of strings
        String[] s = new String[n];
        for(int i=0;i<n;i++)
            s[i] = stdin.nextLine();
        int q = Integer.parseInt(stdin.nextLine()); // Number of queries
        String[] sq = new String[q];
        int[] no = new int[q]; // Number of occurences
        Arrays.fill(no, 0);
        for(int j=0;j<q;j++){
            sq[j] = stdin.nextLine();
            for(int i=0;i<n;i++){
                if(s[i].equals(sq[j]))
                    no[j]++;
            }
        }
        for(int j=0;j<q;j++)
            System.out.println(no[j]);        
    }
}
