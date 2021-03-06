## The purpose of this project is as follows:
This project takes data from PR-Assist reports and the Current Job Report from CUNYfirst to create iterable objects for automation.
## Here's some back story on why I needed to build this:
This is needed to procedurally determine data to be fed into the automation process and input into the system of record. Having both the pipeline and the automation allows the automation to run continuously without human input.
##This project leverages the following libraries:
pandas, numpy, fuzzywuzzy
##In order to use this, you'll first need do the following:
Yes. The user must change the file folder location to one that has both reports from PR-Assist and the CJR. The first report from PR-Assist, the paf report, is obtained by attempting to print all PAFs from the search screen in HR or PR view, then outputting as Excel workbook. The second is the Employee PAF Report available from the reports page. The CJR is obtained in CUNYfirst HCM, if and only if you've been given the role to run it. Ensure that all files are in place in the folder before running. Run CJR effective toay.
##The expected frequency for running this code is as follows:
Daily