# Debloat-Windows-10
Debloat Windows 10

Trying to Debloat Windows 10 is getting ridiculous and as a system admin it is soul crushing to see all that performance go to waste on the botched attempt by Microsoft to do an Appstore and its apps (I’m looking at you Candy Crush). Luckily some admins have worked tirelessly to give us a solution that works considerably well. Lets Start!

October 2020 Update

If you are coming here from the YouTube video I have taken all the scripts below and a system admin script I used a lot in the past to make a streamlined debloat script. This script will optimize Windows and can be run multiple times if you have an update ruin all the optimizations. I have also made it very easy to launch. Here is the source files: https://github.com/ChrisTitusTech/win10script

If you want to just run this on any system, you can easily copy and paste this into a Admin Powershell prompt and watch it do everything for you. It does have two prompts based on user feedback. Let me know what you think below!


**********************************************************************************
Powershell

iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JJ8R4'))


**********************************************************************************

What this script does

Installs Chocolatey, Notepad++, Irfanview, VLC, Java, and asks if you want Adobe Reader or Brave.
Removes all Windows Store Apps EXCEPT office, xbox, and WSL.
Removed Telemetry
Disables Cortana
Deletes various schedules tasks that rebloat the system
Removes Other Bloatware (Candy Crush, etc.)
Fixes problems that other scripts causes (lock screen and personalization options restricted)
Based on User feedback, this no longer uninstalls OneDrive or Office.
