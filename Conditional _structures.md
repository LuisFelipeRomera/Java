# Conditional Structures

## If Else

You can do conditional arguments with `if ("condition") {"action"}` and add a second action if the condition is not achieved with `else {"action"}`

```java
import java.util.Scanner;

public class example {
  public static void main(String args[]) {

    Scanner reader = new Scanner(System.in);

    double grade;

    System.out.print("type your grade: ")

    grade = reader.nextDouble();

    if ( grade > 5 ) {

      System.out.println("Approved");

    } else {

      System.out.println("failed");

}
  }
}
```

## Switch Case

You can use the *switch case* command if you have different commands for different interger values:

```java
import java.util.Scanner;

public class example {

  public static void main(String args[]) {

    Scanner reader = new Scanner(System.in);

    int stage;

    System.out.print("Enter the modification stage of your car: ");

    stage = reader.nextInt();

    switch (stage) {

      case 1:
        System.out.println("Sport filter and exhaust");
        break;

      case 2:
        System.out.println("Sport downpipe and fuel pump");
        break;

      case 3:
        System.out.println("Bigger turbo or supercharger");
        break;

      default:
        System.out.println("Invalid stage");

    }

  }

}
