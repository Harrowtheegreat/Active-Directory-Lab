# Active-Directory-Lab
A browser-based Active Directory Users and Computers simulator for practicing help desk and sysadmin tasks

Account tasks: Reset passwords, enable/disable accounts, and unlock locked-out users.
Add new user : Add a new users.
Security log: Every action is logged with its real Windows event ID (4720, 4724, 4740, 4767, etc.).



This simulation  helps me because it lets me practice real IT work without needing a real network.

No setup: Real AD needs a Windows Server, VMs, and licenses. This runs in a browser.
Safe to break things: You can delete users or lock accounts without hurting anyone, then reset.
Matches real help desk tickets: Password resets, lockouts, disabled accounts, and group access are some of the most common tickets.
Teaches PowerShell: You practice the same cmdlets used on the job.
Builds audit skills: The security log shows real event IDs, so you learn how to trace what happened.



<h3> locked-out account/ disabled account. </h3>


Here i have two accounts that are in the need of service 
one user is experiencing and  locked out account.
why might happen ? 

A user might be locked out because of:

Too many wrong passwords
Still using an old password after a change
A phone or app saving the old password
Caps Lock being on
Someone trying to guess their password

And if the account is disabled

An account might be disabled because:

The employee left the company
They're on long-term leave
It's a new account not ready to use yet
Suspicious activity or a security concern
A temporary or contractor account expired
An admin disabled it by mistake

<img width="1902" height="811" alt="Screenshot 2026-10-03 194801" src="https://github.com/user-attachments/assets/f9f650aa-5330-49cc-afe5-a658d8ddf9bf" />

In this section i unlocked user locked account and enable  a disabled


<img width="1912" height="795" alt="Screenshot 2026-10-04 084439" src="https://github.com/user-attachments/assets/596df0b1-e57b-427f-b5be-5d27b9715938" />


<h3> Creating a New User </h3>  


In this section i am creating a new user account 
why? you ask 

Help desk creates a new user account when:

A new employee is hired
A contractor or intern starts
Someone returns after leaving the company
An employee needs a separate admin account
A shared or service account is needed for a team or system
A test account is needed for training or troubleshooting



<img width="1911" height="837" alt="Screenshot 2026-10-04 093254" src="https://github.com/user-attachments/assets/d3e4d89b-07de-4005-bf57-caa4bbb18e02" />




In this Section i created three new account users



<img width="1916" height="837" alt="Screenshot 2026-10-04 104348" src="https://github.com/user-attachments/assets/4c02c676-fcac-4ff6-85c4-d81a3f7f5c0f" />


In this section I created a new user while assigning them to a computer giving them a basic password which they can change later or keep depending on the company  


<img width="1917" height="830" alt="Screenshot 2026-10-04 111626" src="https://github.com/user-attachments/assets/57115afb-70f2-4290-be6b-f942638ae60a" />



In the properties section it shows you details such as 

Name and full path (distinguished name)
Status: Enabled, Disabled, Locked out, or Must change password
Logon name and UPN (email-style sign-in)
Job title, department, email, phone, description
Bad sign-ins (for example, 3 of 5)
Last sign-in, password last set, and date created
Groups they belong to

<img width="1907" height="834" alt="Screenshot 2026-10-04 112354" src="https://github.com/user-attachments/assets/13254823-9b9a-4f77-895f-c587de37ceee" />


<h3>Security log Section /h3>


The security log is important because it:

Shows who did what and when, so every change can be traced
Helps troubleshoot, like finding why a user got locked out
Spots attacks, such as many failed sign-ins in a row
Supports investigations after a security incident
Proves compliance, since audits often require activity records
Keeps admins accountable for changes they make


<img width="1915" height="760" alt="Screenshot 2026-10-04 160745" src="https://github.com/user-attachments/assets/b85f6a5f-986e-46ea-a037-6b9b8a776865" />
