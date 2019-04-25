# Add_Remove_ADMembership

The code provided was used in my Active Directory class.

This code allows a users to do bulk addition and removal of user membership in security groups in a domain from a CSV file with powershell.

The script works by reading in the CSV file, creating variables based on the column names. 

From there the code loops stating that based on the action you want "Add" or "Remove" in the CSV will create or delete the 
membership to the security group stated in the CSV file.

Code is documented in powershell, please let me know if it does not work or if you have additional questions.
