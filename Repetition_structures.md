# Repetition Structures

## For

For repetition structures, you can use `for ("initial value"; "condition", "increment") {"command"}`

```java
// Counting machine

import java.util.Scanner;

public class example_for {

  public static void main(String args[]) {

    int num;

    Scanner reader = new Scanner(System.in);

    System.out.print("Enter your number: ");

    num = reader.nextInt();

    reader.close();

    int i;

    for (i = 1; i <= num; i++) {

      System.out.println(i);
    }
  }
}
```
## While

You can also use `while ("condition") {"command"}`, but you have to atribute a value to "i" before the function and put the increment inside the command.

```java
// Counting machine

import java.util.Scanner;

public class example_while {

  public static void main(String args[]) {

    int num;

    Scanner reader = new Scanner(System.in);

    System.out.print("Enter your number: ");

    num = reader.nextInt();

    reader.close();

    int i = 1;

    while (i <= num) {

      System.out.println(i);

      i++;
    }
  }
}
```

## Do-While

You can also use `do {"command"} while ("condition")` but in this way, the command is going to be executed once independent of the condition.

```java
// Counting machine

import java.util.Scanner;

public class example_dowhile {

  public static void main(String args[]) {

    int num;

    Scanner reader = new Scanner(System.in);

    System.out.print("Enter your number: ");

    num = reader.nextInt();

    reader.close();

    int i = 1;

    do {

      System.out.println(i);

      i++;

    } while ( i <= num );
  }
}
```
