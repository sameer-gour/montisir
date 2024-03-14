//# montisir
//this is my first git repository and this is my collige work
import java.util.Scanner;

public class monti {

    public static void question1(){
        System.out.println("I am Sameeralam gour");
    }

    public static void question2(){
        Scanner r = new Scanner(System.in);
        System.out.print("Enter var 1 -> ");
        int var1= r.nextInt();

        System.out.print("Enter var 2 -> ");
        int var2 = r.nextInt();

        int sum = var1 + var2;

        System.out.println("var1 + var2 -> " + sum);

    }

    public static void question3(){
        // find the maxium & minimam rang of data type

        System.out.println("integer");
        System.out.println("MIN ->"+ Integer.MIN_VALUE);
        System.out.println("MAX -> " + Integer.MAX_VALUE);

        System.out.println("float");
        System.out.println("MIN ->"+ Float.MIN_VALUE);
        System.out.println("MAX -> " + Float.MAX_VALUE);

        System.out.println("DOUBLE");
        System.out.println("MIN ->"+ Double.MIN_VALUE);
        System.out.println("MAX -> " + Double.MAX_VALUE);

        System.out.println("BYTE");
        System.out.println("MIN ->"+Byte.MIN_VALUE);
        System.out.println("MAX -> " + Byte.MAX_VALUE);

        System.out.println("SHORT");
        System.out.println("MIN ->"+ Short.MIN_VALUE);
        System.out.println("MAX -> " + Short.MAX_VALUE);
        
    }

    public static void question4(){
        //swap number without usiging 3th varabile
        Scanner r = new Scanner(System.in);
        System.out.print("Enter a -> ");
        int a= r.nextInt();

        System.out.print("Enter b -> ");
        int b = r.nextInt();
        
        a = a+b;
        b= a-b;
        a = a-b;

        System.out.println("after swap a-> "+a);
        System.out.println("after swap b -> "+b);
    }

    public static void question6(){
        //print table input user

        Scanner r = new Scanner(System.in);
        System.out.print("Enter table-> ");
        int table= r.nextInt();

        for(int i=1; i<=10; i++){
            System.out.print(table +" * "+ i +" = "+ table*i );
            System.out.println("");
        }
       

    }

    public static void question8(){
        //sum to given two interger if two values are same return the tripal of sum 
        Scanner r = new Scanner(System.in);
        System.out.print("Enter var 1 -> ");
        int var1= r.nextInt();

        System.out.print("Enter var 2 -> ");
        int var2 = r.nextInt();

        int sum = var1 + var2;

        if (var1 == var2){
            System.out.println("var1 + var2 -> " + sum*3);
        }else{
            System.out.println("var1 + var2 -> " + sum);
        }
        
    }

   /* public static void question9(){
        // sum of first of n prime number
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();
        
        int sum=0;     
        int prime; 
        for(int i=1; i<=n; i++){
            for(int j=2; j<=n; j++ ){
                if(i%j == 0 || j%2 == 0){
                    System.out.println("prime");
                }
                else {
                    System.out.println("c");
                }
            }
            } 
             
       
        System.out.println(sum);
    }*/

    public static void question13(){
// print sum of n natrual number

        int sum =0;
         
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

        for(int i=1; i<=n; i++){
            sum = sum +i;
            
        }
        System.out.println(sum);

    }

    public static void question14(){
        
        int sum =0;
         
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

        for(int i=1; i<=n; i++){
            sum = sum +i;
            
        }
        int avg = sum/n;
        System.out.println(sum);
        System.out.println(avg);
    }

    public static void question15(){
        // print table vartical 1 to n

        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

        for(int i=1; i<=n; i++){
            System.out.println("    " +i+" Table");
            for(int j=1; j<=10; j++){

                System.out.println(i+" * "+j+" = "+i*j);
            }
            System.out.println("");
        }
    }

    public static void question16(){
        // print ractangle traingle or astrik number
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

       for(int i=1; i<=4; i++){
        for(int j=1; j<=4; j++){
            System.out.print(".");
        }
        System.out.println("");
       }

       System.out.println("");

       for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i; j++){
            System.out.print(" ");
        }
        for(int j=1; j<=i; j++){
            System.out.print(" *");
        }


        System.out.println("");
       }

        
    }

    public static void question20(){
        int fact=1;
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

        for(int i=1; i<=n; i++){
            fact = fact*i;
        }
        System.out.println(fact);
    }

    public static void question25(){
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

       if(n%2==0){
        System.out.println("even");
       }else{
        System.out.println("odd");
       }
    }

    public static void question26(){
        // 
        Scanner r = new Scanner(System.in);
        System.out.print("Enter n -> ");
        int n= r.nextInt();

        System.out.println("Even");
        for(int i=1; i<=n; i++){
           
            if(i%2 == 0){
                System.out.println(i);
        }
    }
    System.out.println("odd");
    for(int i=1; i<=n; i++){
       
        if(i%2 != 0){
            System.out.println(i);
    }
}

}

public static void question32(){
    //revers number
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter n -> ");
    int n= sc.nextInt();
    int r=0;
    while (n!=0) {
r = n%10;
System.out.print(r);
n=n/10;
      
    }
}

public static void question35(){
    // print factrual and sum of factural
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter n -> ");
    int n= sc.nextInt();
    int fact=1;
    int sum=0;
    for(int i=1; i<=n; i++){
        fact = fact*i;
        System.out.println(i+"-> "+fact);
        sum = sum +fact;
    }
     System.out.println("sum-> "+sum);
}

public static void question48(){
    // take arary by user and print
    Scanner sc = new Scanner(System.in);
    System.out.print("enter array size -> ");
    int size = sc.nextInt();    
    int arr[] = new int[size];

    for(int i=0; i<size; i++){
            arr[i] = sc.nextInt();
    }

    for(int i=0; i<=arr.length-1; i++){
        System.out.print(arr[i]+" ");
    }
}

public static void question49(){
    // revers array
    int arr [] = {1,2,3,4,5,6,7,8,9};
    
    for(int i=arr.length-1; i>0; i--){
        System.out.println(arr[i]);
    }
}

public static void question49_secind_mathed(){
    // in this mathod question is take less time complecte n(0)
    
    int arr[]= {1,2,3,4,5};


    int start = 0; 
    int end   = arr.length-1;

    while (start < end) {
        int temp = arr[end];
        arr[end]= arr[start];
        arr[start]= temp;
        start++;
        end--;
    }

    for(int i =0; i<arr.length; i++ ){
        System.out.println(arr[i]+"");
    }
}

public static void question50(){
    // sum of array
    int arr [] = {1,2,3,4,5};
    int sum =0;
    for (int i=0; i<arr.length-1; i++) {
        System.out.println(arr[i]);
         sum = sum +arr[i];
    }System.out.println("sum -> "+sum);
}

public static void question51(){
    // copy array elemint
    int arr[] = {1,2,3,4,5};
     int arr2[] = new int [arr.length];

     arr2 = arr;

     for(int i=0; i<arr2.length; i++){
        System.out.println(arr2[i]);
     }

}

public static void question52(){
    //count dublicar elemint
int num[]= {1,2,3,3,2,1};
int count=0;
 
 
for(int i=0; i<=num.length-1; i++){
   for(int j=i+1; j<=num.length-1; j++){
    if(num[i] == num[j])
    count++;        
   }
}
System.out.println(" "+count);

    }

public static void question53(){
    // find unice elemint in array
    int num[]= {1,3,4,5,6};
    int unique=0;
     
     
    for(int i=0; i<=num.length-1; i++){
       for(int j=i+1; j<=num.length-1; j++){
        if(num[i] != num[j])
        unique++;        
       }
    }
    System.out.println(" "+unique);

}

public static void question55(){
    //maxsemam & minimam elemint 
    int arr[] = {11,2,3,4,5,8,1};
    int minimam = Integer.MAX_VALUE;
     
    for(int i=0; i<arr.length; i++){
        if(minimam > arr[i]){
                minimam = arr[i];
        }
        
    }
    System.out.println("smallest elemint ->  "+minimam);

    // maximam elemint
    
    int maximam = Integer.MIN_VALUE;
    
    for(int i=0; i<arr.length; i++){
        if(maximam < arr[i]){
                maximam = arr[i];
        }
        
    }
    System.out.println("bigest elemint ->  "+maximam);

}

public static void question65(){
    // binary tringale
    int n=5;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            if((i+j)%2==0){
                System.out.print(1);
            }else{
                System.out.print(0);
            }

        }
        System.out.println("");
    }

}

public static void question66(){
    // print dimand paratine
    int n=9;
    for(int i=1; i<=n; i++){
        for(int j=i; j<=n-1; j++){
            System.out.print(" ");
        }
        for(int j=1; j<=i; j++){
            System.out.print("* ");
        }
        System.out.println("");
    }
    for(int i=n; i>=1; i--){
        for(int j=i; j<=n-1; j++){
            System.out.print(" ");
        }
        for(int j=1; j<=i; j++){
            System.out.print("* ");
        }
        System.out.println("");
    }
}

public static void question67(){
    //floyds tringal
    int n=5;
    int count=1;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            System.out.print(""+count);
            count++;
        }
        System.out.println("");
    }
}

public static void main(String[] args) {
           question65();
    
}
}
