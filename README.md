# RockPaperScissors_Java
A game created using the Java programming language. Users will enter their choice between 'rock', 'paper', and 'scissors'. Then the computer will randomly pick one of the same values. The program will then declare the winner.


## Step 1: 

Import the **Scanner** utility:

```java
import java.util.Scanner;
```

## Step 2:

Create the RockPaperScissors class:

```java
public class RockPaperScissors {
    public static void main(String[] args) {
}
```

## Step 3:

Instantiate the **Scanner** instance:

```java
Scanner scan = new Scanner(System.in);
```

## Step 4:

Introduce the game | Ask user if they would like to play and wait for their input:

```java
        System.out.println("Let's play Rock Paper Scissors.");
        System.out.println("When I say 'shoot', Choose: rock, paper, or scissors.\n");
        System.out.println("Are you ready? Write 'yes' if you are.");

    //Task 1: See if the user wants to play. 
        String ready = scan.nextLine(); 
```