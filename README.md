## Introduction

In this project, I manually create analytic rules in Microsoft Sentinel that will ultimately generate incidents for certain events within this environment. 


## Created a custom KQL query for brute force attempt against the Windows virtual machine 'Windows' rule. 
<img width="960" alt="Screenshot 2024-05-30 at 12 23 07 PM" src="https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/704abc63-7029-40cb-9010-6bfe4903ec7d">


## Created a scheduled query rule in Sentinel that links to the MITRE ATT&CK Framework. 
![Screenshot 2024-05-30 at 12 30 27 PM](https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/f28bdf3e-9295-4b93-837a-213ea9d8c635)


## Added the custom query and enabled entity mapping to allow Sentinel to correlate data and recognize events in other resources.  
![Screenshot 2024-05-30 at 12 37 34 PM](https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/3bf8c30f-61ff-4de9-8d6c-f9404d6c9b47)


## Group alerts together 
<img width="960" alt="Screenshot 2024-05-30 at 12 38 45 PM" src="https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/ccd566ab-49c5-43f0-a010-d16e55f7ea10">![Screenshot 2024-05-30 at 12 40 52 PM](https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/c3684796-cf07-4bf7-9c21-f3196a3af996)


## Create rule
![Screenshot 2024-05-30 at 12 44 25 PM](https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/6b3cd087-5a62-4a9b-bc86-d092e1ebb3b5)


## View Incident
![Screenshot 2024-05-30 at 12 44 49 PM](https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/e8e45c3e-1f98-4104-b319-6aac32fb6f5a)


## Investigate Incident
![Screenshot 2024-05-30 at 12 46 14 PM](https://github.com/jerrycoriolan/Manually-creating-analytics-rules-in-Sentinel/assets/168882662/11bf2921-89c0-4cce-b3b5-99968d6fd9ae)



## Conclusion

Created an analytics rule in Sentinel that will be used to spin up incidents for events taking place and enabled entity mapping to allow Sentinel to correlate data and recognize events in other resources for investigating incidents. 
