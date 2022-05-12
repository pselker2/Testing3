# Cisco Kiosk Mode Demo
### This demo enables calling from a Webex Desk or Board system using a customizable web page.

## **Overview**

This Kiosk Mode demo enables a user to choose from three options to get support.  After the user chooses an option, a call will be setup with the subject matter expert.

Below are instructions on how to enable an environment to execute this demo

---

### **Table of Contents**

- [Create a website to host the Kiosk Mode demo](https://github.com/pselker2/KioskModeDemo/#Create-a-website-to-host-the-Kiosk-Mode-demo)
- [Add a new repo for the code](https://github.com/pselker2/KioskModeDemo/#Add-a-new-repo-for-the-code)
- [Copy files to your computer](https://github.com/pselker2/KioskModeDemo/#Copy-files-to-your-computer)
- [Customize files for your demo](https://github.com/pselker2/KioskModeDemo/#Customize-files-for-your-demo)
- [Test the new website](https://github.com/pselker2/KioskModeDemo/#Test-the-new-website)

---

### **Create a website to host the Kiosk Mode demo**

1. Go to [Quickstart for GitHub Pages](https://docs.github.com/en/pages/quickstart)  
2. Complete the following sections:
    - Creating your website
    - Changing the title and description
        - Stop when you reach the "Next Steps" section
    - (It can take up to 20 minutes for the website to get published)
    
---

### **Add a new repo for the code**

1. Click the "+" sign in the upper right section of your GitHub page 
2. Select New repository 
3. Enter a name in the "Repository name" box (ex: KioskDemo)
4. In the Choose a license section, you can choose any license
    - If you have no preference, select the MIT License
5. Leave the other setting with the default values
6. Click the green "Create repository" button
        
---

### **Copy files to your computer**

1. Go to the https://github.com/pselker2/KioskModeDemo repo
2. Click the green "Code" button
3. Select Download ZIP
4. Open the ZIP file in an empty directory and verify you have all the files.
5. Go to the new repo you created in the previous section
    - https://github.com/(username)/(KioskDemo)
6. Click on the "Add file" button
7. Select "Upload files"
8. Drag and drop the following folders and files:
    - assets folder
    - index.html file
    - src folder
9. Scroll to the bottom of the page and click the green "Commit changes" button
10.  All the files and folders should now be in your new repo

---

### **Customize files for your demo**

Files can be edited via two differnt methods:
1. Open the file in the repo
    - click on the file
    - click on the pencil in the upper right
    - make the edits 
    - scroll to the bottom and click the green "Commit changes" button
2. Open the file with the editor/IDE on your computer
    - open the file the editor/IDE
    - make changes
    - save changes
    - upload the new file to the repo using the same procedure in the previous section



1. Open src/main.js
2. Modify line 22
    - From:  pselker
    - To:    (your cisco ID)
3. Optional:  modify line 23 and 24 to additional sip addresses
4. Save the updated file

5. Open assets/images/ folder
6. Find the photos to upload
7. Change the name of the photo for "Loan" to avatar1.jpg
8. Change the name of the photo for "Advice" to avatar2.jpg
9. Upload the new photos you want to display

10. Open assets/style.css
11. If you want to change the photo for "Credit"
12. Modify line 107
    - From:  ahauge.png
    - To:    avatar3.jpg
13. Save the updated file
14. Upload the new avatar3.jpg file to the /images/ folder

---

### **Test the new website**

1. Go to the web admin of your Webex desk or board endpoint
2. On the left click Settings
3. In Serach box type "Kiosk"
4. Change Mode to On
5. URL:  https://(username).github.io/(KioskDemo)/
6. Save
