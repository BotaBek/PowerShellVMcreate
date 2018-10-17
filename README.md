# PowerShellVMcreate
CreateVMFromTemplate.ps1 takes input from CSV files and builds a new VMWARE Virtual Machine based on the provided specifications.

Before running the script first populate csv files with the required server details:
	InputVMComputeSettings.csv contains details of server settings to be configured in the build
	InputAdditionalVMDisks.csv contains a list of disk sizes for the creation of any additional harddisks for the ne VM.

Use the Get_AD_Credentials.ps1 script to generate a credential file using the credentials of an account with rights to join the new VM to the domain.
