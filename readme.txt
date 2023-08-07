To run on Windows:

Open Shell:
Win + r => powershell => Enter

Change Directory:
cd Path/To/Folder/Containing/Exe 	E.G C:\Users\RoryF\Vodafone\

Run this command from shell and replace File arguments with correct file paths for 
1: Employee Data - Ensure Excel file is saved as a CSV file (UTF8)
2: Contract Template (PDF)
3. Output folder location for contracts - Ensure trailing \ on file path

./VodafoneContractSystem.exe 'C:\Users\RoryF\Vodafone\employeeData.csv' 'C:\Users\RoryF\Vodafone\ContractTemplateFinalFields.pdf' 'C:\Users\RoryF\Vodafone\Contracts\'