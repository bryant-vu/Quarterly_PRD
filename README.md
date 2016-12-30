# Quarterly_PRD
Rule 1173

Quarterly_PRD_1173.exe is intended for use during LTR's Quarterly 1173 reporting.

- Pressure data captured in 1 minute intervals; stored in a csv file.

- Every calendar quarter, user is required to indenfy periods of exceedances above setpoint.

- Print out timestamps and pressure data of exceedances.

#The following provides background information:

1) LTR records data on 12 pressure relief devices (PRDs) on a minute basis.

2) LTR reduces PRD pressure data each quarter to ensure no exceedances occurred.

		a) An exceedance is defined as a recorded pressure above the PRD’s setpoint.

3) Most exceedances result from Sulfatreat changeouts. 

		a) Verify that these exceedances occurred during ST changeout and that operators did not observe emissions.

4) The program will output an Excel file titled “PRD_Data_YYYY_MM” at the location of the ‘E’ and ‘H’ files. (For example, if the ‘E’ and ‘H’ files are located in a folder titled “Data”; the program will create “PRD_Data_YYYY_MM” in the “Data” folder).

5) The program requires both ‘E’ and ‘H’ files to be fed in at the same time, with their specific names, in the original DCS format -- otherwise the script will not execute properly.


