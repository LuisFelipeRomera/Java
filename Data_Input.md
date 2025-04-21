# Data input

To input data you must first import the scanner class `java.util.Scanner` (*"ctrl + shift + o"* Eclipse shortcut) .

Inside the `main` function, you must declare the scanner with `Scanner "name of the scanner" = new Scanner(System.in)`.

To atribute a value in the keyboard to a variable, you must use `"type of data" "name of the variable" = "scanner".next"Data type"()` .

At last, you must close the scanner with `"scanner".close()`.

If I have an integer variable that must receive data from the keyboard, calling my scanner "reader":

 ```java
import java.util.Scanner;
  public class example {
    public static void main(String args[]) {
      Scanner reader = new scanner(System.in);
      int var = reader.nextInt();
    }
} 
