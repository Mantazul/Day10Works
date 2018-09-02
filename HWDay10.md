# Day10Works
Day10 homework 
package Pyramid;
public class Pyramid {
        public static void main(String[] args) {
            int level = 5;
            for(int i=0; i<level; i++){
                for(int j=0; j<level-i; j++){
                    System.out.print(" ");
                }
                for(int k=0; k<=i; k++){
                    System.out.print("* ");
                }
                System.out.println("");
            }}}

package SelectionSort;

public class SS1 {
    public static void main(String[] args) {
        int[] array = {2, 3, 1};
        for (int j = 0; j < array.length-1; j++) {
            int min = j;
            for (int i = j+1; i < array.length; i++) {

                if (array[i] < array[min])
                    min = i;

                int temp = array[min];
                array[min] = array[j];
                array[j] = temp;

                for (int n = 0; n < array.length; n++) {
                    System.out.println(array[n]);
                }
            }} }}
