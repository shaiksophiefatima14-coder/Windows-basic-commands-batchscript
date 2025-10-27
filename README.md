# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="414" height="111" alt="Screenshot 2025-10-27 172427" src="https://github.com/user-attachments/assets/5c7c2fb7-7946-48f3-9b5e-90bf289f2b00" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="434" height="98" alt="Screenshot 2025-10-27 172517" src="https://github.com/user-attachments/assets/bb2af3f3-4395-424e-96ec-98ac0ec868e9" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="626" height="311" alt="Screenshot 2025-10-27 172722" src="https://github.com/user-attachments/assets/1a47e6da-6c2f-454a-8ef4-e53f7f711f86" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="616" height="147" alt="Screenshot 2025-10-27 172808" src="https://github.com/user-attachments/assets/4806dca1-2223-47c3-836d-4258ee49de13" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="595" height="171" alt="Screenshot 2025-10-27 172855" src="https://github.com/user-attachments/assets/1b73c0ed-42ce-4ce8-89ff-969f720647bf" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="486" height="49" alt="Screenshot 2025-10-27 175100" src="https://github.com/user-attachments/assets/fd8c5ec3-bbc0-4d13-ae82-1b5bfdc32f87" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="604" height="253" alt="Screenshot 2025-10-27 172942" src="https://github.com/user-attachments/assets/e701b609-c078-4cc1-b0b0-8509b0ffa7de" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="472" height="227" alt="Screenshot 2025-10-27 173021" src="https://github.com/user-attachments/assets/a03891f0-f153-49d4-9ac8-5b5b4400231b" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="611" height="228" alt="Screenshot 2025-10-27 173102" src="https://github.com/user-attachments/assets/ede83ff4-9701-405f-be31-be685d1ad271" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="516" height="330" alt="Screenshot 2025-10-27 173414" src="https://github.com/user-attachments/assets/36038afd-a3f8-4ff0-b994-e97b4e8f8aed" />




## OUTPUT
<img width="415" height="86" alt="Screenshot 2025-10-27 173312" src="https://github.com/user-attachments/assets/8f092468-d2f3-4dd7-887b-66d8bbd9b066" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="624" height="212" alt="Screenshot 2025-10-27 173544" src="https://github.com/user-attachments/assets/94fd4f8b-c3a4-42f8-8824-80e66d42bed3" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="510" height="165" alt="Screenshot 2025-10-27 173629" src="https://github.com/user-attachments/assets/8cb2cea9-74cd-49bd-a936-0112c3e3a23c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="612" height="193" alt="Screenshot 2025-10-27 174000" src="https://github.com/user-attachments/assets/2f5fb071-5553-44ad-901a-eb185f0138f4" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="501" height="395" alt="Screenshot 2025-10-27 174127" src="https://github.com/user-attachments/assets/1af5b9bf-a1a1-4830-864b-44e7548be585" />



# RESULT:
The commands/batch files are executed successfully.

