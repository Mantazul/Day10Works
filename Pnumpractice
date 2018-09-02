# Day10Works
Day10 homework 
package PM1;

public class PrimeNumber {
    public static void main(String[] args) {
        int c = 0;
        for(int i=1; i<100; i++){
            if(i==1){
                System.out.println(i);
            }else{
                if(isPrime(i)){
                    c++;
                    System.out.println(i);
                }else{

                }
            }
        }
        System.out.println("Total Number of Prime Numbers So Far: " + c);
    }
    public static boolean isPrime(int n){
        if(n%2==0)return false;
        for(int i=3; i*i<=n; i+=2){
            if(n%i==0) return false;
        }
        return true;
    }
}
