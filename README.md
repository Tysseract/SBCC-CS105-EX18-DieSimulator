## Exercise: DieSimulator (3 Extra Credit Points)

The project name of this exercise is **DieSimulator** 

The purpose of this assignment is to give you a little practice problem solving, looking up Java documentation, writing unit tests, and running unit tests.

### Problem Description

You are creating an object that will simulate rolling a die. A die (also called a dice) has a good description in wikipedia. The relevant part for us is that when we roll a die it will give us a random number between 1 and 6. Every time we roll it we get a new number. Of course, we can roll the same number multiple times in a row but we should eventually get a different value.

Your job is to write the code for a method called rollTheDie() that is part of the DieSimulator object. The place where your code goes is marked clearly by comments. You will also need to place your test code into **DieSimulator.java** and when that is working correctly you need to down load the **DieSimulatorTester.java** code and run that to see if your code passes the test.

### Getting Started

Similar to previous exercises, start this exercise using the technique on the web page titled [How to Start Every Project in this Class](http://crowd.cs.sbcc.edu:7990/projects/CS105F2016/repos/allan.knight/browse/HowToStartEveryProject.md). When complete you should have a **DieSimulator.java** file ready for you to fill with code. Replace all of the code present with the code contained in the box below:

```java
/**
 * CS 105 Theory & Practice I
 * CRN: [CHANGE THIS TO YOUR INFORMATION]
 * Assignment: DieSimulator
 * 
 * Statement of code ownership: I hereby state that I have written all of this
 * code and I have not copied this code from any other person or source.
 * 
 * @author [CHANGE THIS TO YOUR INFORMATION]
 */
package edu.sbcc.cs105;

/**
 * This class tests the DieSimulator object.
 *
 */
public class Main {

    /**
     * This method creates a DieSimulator object and repeatedly invokes its
     * rollTheDie method. The hope is that there are enough calls here to show
     * that the simulator works properly.
     * 
     * @param args
     *            command line values. Not used in this example.
     */
    public static void main(String[] args) {
        DieSimulator ds = new DieSimulator();

        System.out.println("    One die roll is " + ds.rollTheDie());
        
        // Add more of these until you are convinced the code works
        // correctly.
        System.out.println("Another die roll is " + ds.rollTheDie());
    }

}
```

You can simply copy the code from the grey box and paste it into the DieSimulator.java file. Go through the code and replace every instance of `[CHANGE THIS TO YOUR INFORMATION]` to the appropriate item. Be sure that the square brackets are included when you replace the text. There are two items that need to be changed. You should then add multiple System.out.println lines as shown in the comments. Add as many as you think you might need to show that your code is functioning properly.

Next, using the same technique you used to create the **DieSimulator.java** file create another file called **DieSimulator.java**. Replace the code in that file with the code in the grey box below:

```java
/**
 * CS 105 Practice & Theory I
 * CRN: [CHANGE THIS TO YOUR INFORMATION]
 * Assignment: DieSimulator
 * 
 * Statement of code ownership: I hereby state that I have written all of this
 * code and I have not copied this code from any other person or source.
 * 
 * @author [CHANGE THIS TO YOUR INFORMATION]
 */
package edu.sbcc.cs105;

import java.util.*;

/**
 * This class simulates rolling a die by generating a random number between 1
 * and 6 inclusive.
 *
 */
public class DieSimulator {

    /**
     * Multiplies an integer input by two.
     * 
     * @return a random integer from 1 to 6 inclusive.
     */
    public int rollTheDie() {
        int randomDieRoll = 0;

        // YOUR CODE GOES FROM HERE




        // TO HERE

        return randomDieRoll;
    }
}
```

Similar to the **DieSimulator.java** file go through **DieSimulator.java** and change the `[CHANGE THIS TO YOUR INFORMATION]` text to the proper items. There are two items to be changed.

You need to add code to generate a random number from 1 to 6 inclusive. To do that you'll need to use the Random object which is a part of the Java library. There is a description of the Random object online. Read this documentation to get an understanding of how to use the Random object. Before running to Google for the answer on how to generate a number from 1 to 6 please spend a little time thinking about it and solve it on your own. Look and see what you have to work with and how you can get the answer you want. Being able to develop that algorithm is a key skill in computer science.

Once you've written your code run the code by single clicking on **DieSimulator.java** in the package explorer and selecting **Run->Run** from the menu or using the keyboard shortcut. Examine the output. Does it do what you want? If not, how can you modify the code to do what you want?

What you've done is create an object that solves a particular problem and then tested it with the code that was found in **DieSimulator.java**. You also properly documented the code using Javadoc. This is a very typical structure for exercises in this class. You will be given a problem which you will solve using one or more objects that you write. In this case there was only one object which was specified by the **DieSimulator.java** class. The test code was found in DieSimulator.java and this code created a DieSimulator object and then used it. It showed the output which can be examined for correctness.

### Running the Unit Tests

Next you'll want to run these unit tests. Start by right-clicking on the `unittest.cs105` package and selecting **Run As -> JUnit Test**. 

To go back to the project view, select the **Package Explorer** tab.

### How to turn in this exercise

The first step of turning in your code is to commit and push your code to GitHub. Once you've completed this step your code will be on GitHub in your repository, not the repository for the class. This will allow you to use all your projects later as a portfolio.

To start the process write click your project and select **Team -> Commit...** and follow the usual procedures.

#### Completing the turn-in process

Now to complete the turn-in process, once you confirmed that your code is on BitBucket, that's it. You don't need to run the unit tests on Bamboo, just commit and push to BitBucket.

