# Data Output

To output data, you must use the command `System.out.print("output")`.
You can also use `println` if you want the output to skip one line after the last console message.
The text must be between **parenthesis** and variables must be added with `+`.

```java
Import java.util.Scanner;

public class example {
  public static void main(String[] args) {
    Scanner reader = new Scanner(System.in);
    int age;
    System.out.print("type your age: ");
    age = reader.nextInt();
    reader.close();
    System.out.println("you are " + age + "years old");
  }
}
