Send Mail Using smtp.live.com
=============================

            

This runbook sends an email through the smtp.live.com service. You can run this runbook by itself or call it from another runbook as part of a larger workflow. 


REQUIRED


An Automation credential asset named 'SmtpLiveCredential' (or some other name) that contains the information for authenticating with smtp.live.com.  You must create this credential asset in this Automation account.  This is the credential you use
 to log in to the hotmail.com, live.com, or outlook.com account.


NOTES


- The From address must be one with authorization to send email through smtp.live.com.


- The SmtpServer value defaults to smtp.live.com.


AUTHOR


Azure Automation Team 


LAST EDIT


2016-6-14


 




 
![Image](https://github.com/azureautomation/send-mail-using-smtp.live.com/raw/master/SendMailLive.png)




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
