In this project I review and update a system's Windows Defender antivirus and firewall configurations. 

## Windows Defender Antivirus

First I will assess the current state of the **Windows Security** settings for the machine. 

These settings can be found by navigating through: 
	1. Click the Windows *Start* button 
	2. Select *Settings* 
	3. Scroll down and select *Update & Security*
	4. Select *Virus and threat protection*

![](Images/Pasted%20image%2020230722130926.png)

The virus and threat protection window provides four different features: 
	1. Current threats 
	2. Virus and threat protection settings
	3. Virus and threat protection updates
	4. Ransomware protection

The **Current threats** section shows that the system has not been scanned for a few years and will need a scan as soon as possible. 

## Step 2 - Update Threat Definitions

Before running any scans, it is important to ensure that the system's **threat definitions** are up to date as these contain threat intelligence and rules on the latest vulnerabilities. Running a scan with outdated threat definitions could result in a threat going undetected. 

In the **Virus & threat protection updates** feature, I run a check for updates to ensure that the system has the latest threat definitions. 

![](Images/Pasted%20image%2020230722132703.png)

## Step 3 - Run an Antivirus Scans

Because of the length of time since the last scan, this system will benefit from a full scan. Windows Security provides tools for quick and custom scans that I will perform before the full scan. 

For this system I will run a: 
	1. Quick scan 
	2. Custom scan for only the downloads folder 
	3. Full scan

Performing a scan will scan files based on the newly updated threat definitions, and after each scan I verify that no threats were found, quarantined, or allowed: 

![](Images/Pasted%20image%2020230722132949.png)



