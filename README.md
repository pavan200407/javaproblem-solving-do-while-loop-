# javaproblem-solving-do-while-loop-
print even numbers from 1 to 10 using do/while loop?
class Main {
    public static void main(String[] args) {
        int num=20;
        int i=1;
       do
       {
           if(i%2==0){
           System.out.println(i);
           }
	        i++;      
       }
       while(i<=num);
    }
}
