# Rule-Based Expert System Based on Edge Enhancement and the Thresholding Method

## Introduction

This rule-based expert system is written in Arity/Prolog32 interpreter. For a detailed information about the expert system please read the PDF file: `Rule-Base_Expert_System`.  

Some preparations must be made before running this program on a Windows box. The following steps may be followed to set up the environment and run the expert system.

1. Downloading and installing the Arity/Prolog32 zipped file.
2. Running the expert system application inside the Prolog interpreter.

## 1.1 Downloading and installing the Arity/Prolog32 zipped distribution file

To download and install the Arity/Prolog32 interpreter, please visit Peter L. Gabel's website at http://petergabel.info/ArityProlog32/InstallingArityProlog32. After downloading, set the following system environment variables.

+ `C:\ArityProlog32\BIN` to your `PATH` variable
+ `C:\ArityProlog32\LIB` to your `LIB` variable
+ `C:\ArityProlog32\INCLUDE` to your `INCLUDE` variable 

After installing the software, you can run the Arity/Prolog32 interpreter by typing the following command in the command prompt: `C:\api32`

## 1.2 Running the expert system application inside the Prolog interpreter

To run the expert system application, `imgexp.ari` Prolog file, download it from the section on GitHub. Go to the directory where you put the `imgexp.ari` file after downloading and run the `api32.exe` interpreter, see **Figure 1**.

In the interpreter, type in Alt-F and select File > Consult File … In the dialog box that pops up, type in the filename `imgexp.ari`, see **Figure 2**. To start the expert system  type `?- begin.` Do not type the `?-`, it is the Prolog interpreter prompt. See **Figure 3**.

Now, you can interact with the expert system, trying out various tool combinations using the thresholding method for edge enhancement, See **Figure 4**.

	Figure 1. The Arity/Prolog32 Interpreter
![Figure_1](https://github.com/user-attachments/assets/4d73b822-b648-403e-ad09-cbfb2d8f84b4)

	Figure 2. Consulting a Prolog file to run
![Figure_2](https://github.com/user-attachments/assets/12fcc614-4711-414e-88ec-501570cfbfd1)

	Figure 3. Starting the Expert System
![Figure_3](https://github.com/user-attachments/assets/20d6e94f-1d78-44c9-829d-41fdc3cae5c1)

	Figure 4. Main Window of the Expert System
![Figure_4](https://github.com/user-attachments/assets/f2fed390-0a45-4164-bddf-29920b89e471)



		
		




