# Hollow-Triangle-Pattern-in-Java
Write a java program to print a Hollow Triangle Pattern



          import java.util.Scanner;

          public class Main {
              public static void main(String[] args) {
                  Scanner console = new Scanner(System.in);
                  System.out.println("Enter Number of Rows:");
                  int row = console.nextInt();
                  for (int i =1; i<= row; i++) {
                      for (int s= 1; s<=row-i;s++){
                          System.out.print(" ");}

                      for (int j=1; j<=i*2-1; j++){
                          if (i==1||j==1||j==i*2-1||i==row){
                              System.out.print("*"+"");
                          }
                          else
                              System.out.print(" ");
                          }
                      System.out.println();
                      }



              }
          }
          
          
          Enter Number of Rows:
          5
                      *
                     * *
                    *   *
                   *     *
                  *********

