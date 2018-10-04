# nus-scantron-mrq

Author: Min-Yen KAN <kanmy@comp.nus.edu.sg>

Scantron Scantools Application and Conversion Profile for Multiple Response Questions for the School of Computing's Scantron Form

This file documents how to use the standard School of Computing Multiple Choice Question (50 Question) worksheet to be used for multiple response questions; i.e. "mark all responses that apply", as opposed to the simple "mark one only" multiple choice questions).

This software is installed and usable on the MCQ machine in the Equipment Room in SoC COM2 #02-63.  If using it elsewhere you will need the two files in the root directory of this repository:

* [Z556.SDS](../master/Z556.SDS) goes in `C:\Program Files (x86)\Scantron\ScanTools Plus\Applications`
* [CS3244.$CP](../master/CS3244.$CP) goes in `C:\Program Files (x86)\Scantron\ScanTools Plus\Profiles`

The latter file may have been renamed on the computer to `556.$CP` or similar.

## Steps for using the application

1. First, launch the application.
   ![Scantools Icon](https://github.com/knmnyn/nus-scantron-mrq/blob/master/images/scantool.jpg?raw=true "Scantool Icon")
2. Select the appropriate application and datafile.
   ![New Datafile](https://github.com/knmnyn/nus-scantron-mrq/blob/master/images/newdf.jpg?raw=true "New Datafile")
3. ![Datafile](https://github.com/knmnyn/nus-scantron-mrq/blob/master/images/datafile.jpg?raw=true "Datafile")
4. Load in your MCQ 50 forms with the reading barcode facing the input of the machine (that is, load the paper sideways)
   ![Load the Scanner](https://github.com/knmnyn/nus-scantron-mrq/blob/master/images/scanner.jpg?raw=true "Load the Scanner")
5. After it completes, you can load in your CSV into Excel.  The results should look like this.  
   ![CSV in Excel](https://github.com/knmnyn/nus-scantron-mrq/blob/master/images/csvinxls.jpg?raw=true "CSV in Excel")

6. I suggest that you convert the CSV file into an Excel spreadsheet so that you can do the scoring more comprehensively in the spreadsheet directly.

## History

I cloned the original 555 application that works for the same 50 MCQ response sheet and renamed it 556 to test out how it might work, hence the ID "556".
