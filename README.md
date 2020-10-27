Disables or Enables all Alert Rules in a given Azure Resource Group.
====================================================================

            

This script gets all the rules in a given Azure Resource Group and either Disables them or Enables them depending on the presence of the Enable switch parameter. Default action (no -Enable) is to disable all the rules. Rules that are currently already disabled
 will stay disabled and vice versa depending on the presence of the Enable switch parameter.


 


*NOTE*


You must be logged into your AzureRMAccount and set to the subscription context that you want to use before calling this script.


 


 

 Two simple functions to either enable or disable the Alert Rules and calling is controlled by a switch statement. Download the full script to see the logic flow.

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
