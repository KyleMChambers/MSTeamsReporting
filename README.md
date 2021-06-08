# MSTeamsReporting
Powershell script - reporting menu for MSTeams
A single script allows you to generate eight different Teams reports.  
The script can be executed with MFA enabled accounts too. 
Exports output to CSV. 
Automatically installs Microsoft Teams PowerShell module (if not installed already) upon your confirmation. 
The script is scheduler friendly. I.e., Credential can be passed as a parameter instead of saving inside the script. 

# Setup and Running the script
Step 2: Start Windows PowerShell as Administrator. 

Step 3: To run this script, you can choose any one of the below methods.  

 Method 1: Execute script with non-MFA account    

**./TeamsReports.ps1**


Method 2: Execute script using MFA account  

**./TeamsReports.ps1 -MFA**

Method 3: Execute script by explicitly mentioning credential (Scheduler friendly) and required action  

**./TeamsReports.ps1 -Action 1 -UserName Admin@Contoso.com -Password XXXX**

## Choosing an Action

You can skip the menu and choose an Action per the below. The out-file will be located in the root directory. 

/TeamsReports.ps1 -Action 3

