# Policy-Tracker
This program tracks the use of Class Policy when running on a student's computer. To run it, paste the code into notepad, save as a .ps1 file, and run in powershell.

Issues:
Sometimes the program labels policy as 'off' when it is on. The temporary fix for this is to lower the threshold of memory usage to label policyagent as on, though this will still sometimes lead to issues where it now labels it as on when it isn't.
