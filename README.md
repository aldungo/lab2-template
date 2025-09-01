# Programming Fundamentals CSCI 1436
## Programming Fundamentals I

Lab Assignment #2

Mass Energy

Due date: 9/9/25 at 11:59 pm

Purpose: A team of physicists need you to prepare a program to calculate the energy contained within some body of mass. You will be using Einstein’s famous equation E = mc2 to accomplish this task. This program will emphasize the following concepts:

* Declaring and using variables
* Declaring and using constants
* Reading user input
* Performing numeric operations
* String concatenation to format output

### Try Me: In-Class 2 Example

To prepare for performing these physics calculations, consider a simpler case: a force is calculated as mass multiplied by acceleration. Write a program that accepts user input for both the mass and the acceleration of an object and then calculate the force being applied to that object. Display the result to the user. The program flow might look like the following: 

```java
Please enter the mass of the object (kg): 10 
Please enter the acceleration of the object (m/s^2): 5 
The force being applied to the object is 50 N. 
```
Let's do a quick warm-up together before starting the main lab. Follow along as I demonstrate each step. We'll build the code together and see how it works in real time.

- In the Java 'InClass2_FirstName_LastName.java`, make your name is in the filename and class header.
- Make sure to import and declare a Scanner for user input.
- Declare three variables: one for mass, one for acceleration, and one for force.
- Print a statement asking the user to enter the mass, then assign their input to the mass variable using input.nextDouble().
- Repeat the process for acceleration: print a prompt and assign the input to the acceleration variable.
- Calculate the force by multiplying mass and acceleration.
- Print the result in a clear sentence showing the force applied to the object.


## Lab Assignment Instructions

### Task Overview
For this lab only, the Java file is already created for you, named `Lab2_FirstName_LastName.java`. Replace FirstName and LastName with your actual name, and do the same in the class header on Line 9. **Note:** In future labs, you will be responsible for creating the `.java` file yourself, including writing the correct class and method headers. This is an important skill for building your own programs from scratch.

**Example:** If your name is John Smith, create `Lab2_John_Smith.java`

### Step-by-Step Instructions for Lab2_FirstName_LastName.java


#### Step 1: Open Your Java File
The file `Lab2_FirstName_LastName.java` is already created for you. Make sure to update the filename and class name with your actual first and last name.

#### Step 2: Add File Header and Class Structure
Add header comments at the top of your file with your name, today's date, and a brief purpose statement. Confirm the class name matches your filename.

#### Step 3: Import and Declare Scanner
At the top of your file, import the Scanner class. In your `main` method, declare a Scanner called `input` to accept input from the keyboard.

#### Step 4: Declare Constant and Variables
Declare a constant of type double called `SPEED_OF_LIGHT` and initialize it to 300000 (the speed of light in km/s). Use the keyword `final`. Then, declare two variables of type double called `mass` and `energy`.

#### Step 5: Request User Input
Prompt the user to input a mass in kg. Use the Scanner to assign the user's input to the `mass` variable.

#### Step 6: Calculate Energy
Calculate the energy using the formula `E = mc^2`, where `m` is mass and `c` is the speed of light. Assign the result to the `energy` variable.

#### Step 7: Display the Result
Print the result to the console, using string concatenation to combine a statement about the result with the value of `energy`. The resulting unit is megaJoules (MJ).

#### Step 8: Add Comments
Add comments in your code describing what each part does and why you wrote it that way.

## Running Your Program

### Method 1: Using the Terminal
1. Open the terminal in your codespace (Terminal → New Terminal)
2. Compile your program:
   ```bash
   javac Lab2_YourFirstName_YourLastName.java
   ```
3. Run your program:
   ```bash
   java Lab2_YourFirstName_YourLastName
   ```
## Testing Your Program


### What Should Happen
When you run your program, you should see a prompt asking for the mass of the object in kg. After entering a value, the program should display the calculated energy in megaJoules (MJ) using scientific notation. For example:

   Please enter the mass of the object (kg): 100
   The energy of the object is 9.0E12 MJ.

If you see a result like this, your program is working correctly!

### Troubleshooting Common Issues
- **Compilation errors:** Make sure you imported Scanner, declared all variables, and used the correct syntax (including semicolons).
- **No output or missing prompt:** Confirm you used `System.out.print()` or `System.out.println()` for both the prompt and the result.
- **Incorrect calculation:** Double-check your formula for energy and that you used the correct variable names.
- **Wrong filename/class name:** Both should use your actual first and last name, and match each other.
- **Typos:** Double-check spelling, capitalization, and punctuation.

## Commit Your Changes
1. Use VS Code's Source Control panel:
   - Click the Source Control icon in the left sidebar
   - Type a commit message describing your changes
   - Click "Commit" then "Sync Changes" to push your code

### Step 3: Verify Submission
After pushing your changes, visit your assignment repository on GitHub Classroom. Confirm that your latest code and commit message appear, and that your files are named correctly. Check the "Actions" tab to see if your code passed the autograding tests.

### Step 4: Submit to Blackboard Assignment
Once you have verified your submission on GitHub Classroom, copy the URL of your assignment repository and submit this GitHub repository link to Blackboard as confirmation that you are DONE.

## Grading Criteria

**Lab2.java (100 points total):**
Criteria: Make sure you have the following in your program:

- Comments describing this program (10 points)
- Importing and declaring the Scanner (15 points)
- Declaring the constant for the speed of light (10 points)
- Declaring the two variables for mass and energy (10 points)
- Requesting the user’s input (10 points)
- Calculating the energy (25 points)
- Displaying the result (20 points)

**InClass2.java (Participation points):**
Full credit is awarded for completing and submitting the in-class exercise, regardless of output or minor errors.

**Remember:** This is your second programming assignment! Take your time, ask questions, and don't worry if it takes a few tries to get everything working. The goal is to learn the process and get comfortable with the tools you'll be using throughout the course.

**Important:** Do NOT edit or tamper with any test files (such as Lab2Test.java or InClass2Test.java). These files are used for autograding and checking your work. In future labs, if test files appear to be modified, you may be contacted to verify the integrity of your submission.