# sentinel-Map
Introduction :
• In this project, we'll go over how to set up a lab for a honeypot utilising the Azure platform from Microsoft and how to aggregate the data the honeypot gathers to Microsoft Sentinel, a security information and event management (SIEM) tool.
 • A honeypot is a security gadget made to lure and catch potential attackers by impersonating a useful component of a network. You may imitate a network environment and gather useful information on potential threats and malicious activities by setting up a honeypot lab on Azure. 
• Once the information has been gathered, it can be forwarded to Microsoft Sentinel for storage and analysis. You can track and handle security risks across your business with the help of Sentinel, a cloud-based SIEM application.
Problem Statement
 • Setup  the Azure Sentinel (SIEM) and connect it to a live 
virtual machine acting as a honey pot. 
• We will observe live attacks (RDP Brute Force) from all 
around the world. 
• We will use a custom PowerShell script to look up the 
attackers Geolocation information and plot it on the Azure 
Sentinel Map.
 • Now a days we are seeing so many cyber attackers are going 
to steal our data by entering in to our network we prevent 
this by using this project.
Methology
 • Setup the Azure Sentinel (SIEM) and connect it to a live 
virtual machine acting as a honey pot. We will observe live 
attacks (RDP Brute Force) from all around the world. We will 
use a custom PowerShell script to look up the attackers 
Geolocation information and plot it on the Azure Sentinel 
Map. Now a days we are seeing so many cyber attackers are 
going to steal our data by entering in to our network we 
prevent this by using this project. 





Flowchart of the system:
 
Implementation Details:
 1. Create Azure Subscription 
• It's easy to sign up for an Azure subscription; just visit https://azure.microsoft.com and 
start a free trial. 
• I signed in after creating it to view the Azure Dashboard. 
2. Create Virtual Machine 
• The resource group enables the grouping of all the resources for this lab so that they 
all have the same lifecycle. Understanding this is crucial because, once the lab was 
finished, I would have to deactivate the resource group in order to stop the resources 
from billing me for services. 
• In the Azure Dashboard, the resource group can be created separately or at the same 
time as the virtual machine. The formation of the Resource Group and the VM are depicted in the next graphic as occurring simultaneously.
3.Firewall turn off / allow all in firewall
 4.Create Log Analytics Workspace
 5.Enable gathering VM logs in Security Center
 6. Connect Log Analytics to VM
 7. Setup Azure Sentinel 
8. Log into VM with Remote Desktop.
 9. Observe Event viewer Logs in VM 
10. Turn of Windows Firewall on VM 
11. Running a powershell script.
12. Get Geolocation.io API Key 13 Run Script To get Geo Data from attackers 
13. Create custom log in LAW to bring in our custom log 
14. Create custom fields/extract fields from raw custom log data
 15. Testing custom fields.
 16. Testing Extracts 
17. Setup map in sentinel with Latitude and Longitude (or country)
 18. Connect Splunk to Microsoft sentinel
 19. Fixing Map plot sizes
 20. Final check on map 
Screen shots of implemented work:
1)	Create Azure subscription  

2) Create Virtual Machine 

3) open Microsoft azure portal 

4.Firewall turn off / allow all in firewall 

5) Create Log Analytics Workspace
  

6) Connect Log Analytics to VM
  
7) Setup Azure Sentinel
  
8)log in to sentinel
  
9) Log into VM with Remote Desktop.
  
10) Observe Event viewer Logs in VM
  
11) Turn of Windows Firewall on VM  
12) Running a powershell script 
13) Get Geolocation.io API Key 13 Run Script To get Geo Data from attackers.
  
14)create custom log in law to bring in our custom log.
  

15)create custom fields/exact fields from raw custom log data.


  

16) Testing custom fields.
  

17) search results.
  

18) Setup map in sentinel with Latitude and Longitude (or country).
  

20) Fixing Map plot sizes
  

21) Final check on map
  
