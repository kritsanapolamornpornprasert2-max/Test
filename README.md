# Test
Test
import java.util.Scanner;//เรียกใช้งานScanner
public class Main {
   public static void main(String[] args) {
       int num;
       String grade = "";//กำหนดตัวแปรSting grade
       Scanner kb = new Scanner(System.in);
       System.out.print("Input : ");
       num = kb.nextInt();
       if(num == 1){
           grade ="Output  I";//ถ้า num = 1 จะได้เลขโรมันเท่ากับ I
       }else if(num == 2){
           grade = "Output : II";//ถ้า num = 2 จะได้เลขโรมันเท่ากับ II
       }else if(num == 3){
           grade = "Output : III";//ถ้า num = 3 จะได้เลขโรมันเท่ากับ III
       }else if(num == 4){
           grade = "Output : IV";//ถ้า num = 4 จะได้เลขโรมันเท่ากับ IV
       }else if(num == 5) {
           grade = "Output : V";//ถ้า num = 5 จะได้เลขโรมันเท่ากับ V
       }else if(num == 6) {
           grade = "Output : VI";//ถ้า num = 6 จะได้เลขโรมันเท่ากับ VI
       }else if(num == 7) {
           grade = "Output : VII";//ถ้า num = 7 จะได้เลขโรมันเท่ากับ VII
       }else if(num == 8) {
           grade = "Output : VIII";//ถ้า num = 8 จะได้เลขโรมันเท่ากับ VIII
       }else if(num == 9) {
           grade = "Output : IX";//ถ้า num = 9 จะได้เลขโรมันเท่ากับ IX
       }else if(num == 10) {
           grade = "Output : X";//ถ้า num = 10 จะได้เลขโรมันเท่ากับ X
       }else {
           grade = "Can’t not convert to roman number, My program support only 1-10";
       }
       System.out.println("=== Program convert arabic to roman ===");
       System.out.println("Input : " + num );//แสดงสิ่งที่ Input
       System.out.println( grade);//แสดงผลลัพธ์


   }
}
