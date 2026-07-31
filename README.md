# Minimum_value

package arrays;

import org.w3c.dom.ls.LSOutput;

public class Minimum_Value {
    static void main() {
        int[] arr={-6,8,14,-2,23,47,4,3,10};
        //int min=arr[0];
        int min=Integer.MAX_VALUE;   //dono me se koi bhi le sakte hai


        for(int i=0;i<arr.length;i++){
            if(arr[i]<min)
                min=arr[i];
        }

        System.out.println(min);



    }
}
