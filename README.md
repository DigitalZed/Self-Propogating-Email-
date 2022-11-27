# Self-Propogating-Email-

By understanding how malware can be spread via email, one can better understand how to protect computers and their users. Many people infect their computers unintentionally by downloading malicious files from their emails. This project explores the spread of malware by sending malicious files out over email. The file downloads Python on the host computer and uses it to further spread itself. With the user granting permission for the file to run once, it is able to alter the computer’s security settings and download third party software, as well as send out emails from the user’s account. This demonstrates the risk of granting permissions to unknown files.

# Usage 

Step 1. Python script to send emails

1. Set up a gmail account
2. Enable 2 factor authentication
3. Create an app password
4. Put the app password as the password in the python script 
5. The file that is being sent by the script must be in the same directory as the script

Step 2. Batch script
1. The .bat file needs to be made into an executable file
2. Open a text file and save it as .exe
3. Go to C:\Windows\System32 and run iexpress.exe as an administrator
4. Select “Create new Self Extracting Drive”
5. Package Purpose: Select “Extract files and run an installation command”
6.Package Title: Enter what you would like to name your .exe
7. Confirmation Prompt: Select “No prompt”
8. License Agreement: Select “Do not display a license”
9. Packaged FIles: Add the bat file
10. Install Program to Launch: Enter cmd /c script.bat in the Install Program field replacing script.bat with the name of your .bat file
11. Show window: Select “Hidden”
12. Finished Message: Select “No message”
13. Package Name and Options: Add the exe file you created in Step 2, #1
14. Configure Restart: Select “No restart”
15. Save Self Extraction: Select “Don’t Save”
