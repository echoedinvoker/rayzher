# **_Process_**

## **Prepare**

- Two send emails with CSV attachments.
- Two CSV files in tmp folder.

## **Greeting**

## **Introducing Case**

### _Endpoint Protection System_

- Detects if the endpoint is accessed by a suspicious IP, and generates an alarm if it is.
- Organize the weekly alerts into a CSV file and send a letter.

### _Database System_

- The contents of the CSV file will be collected in a specified folder and uploaded to the database.
- It has a dedicated front-end page.
  - The "Canvas" page can be customized to present the data in the database visually.
    - You can do some filtering, here you can choose the data needed for ~ months ago.

### _Email System_

- Attaching result of Canvas to mail, and send to multiple relative members.

## **First Skill**

### _Low-Code_

- Use JavaScript, so the resources on the internet are very abundant.
- Each module is actually mainly to help us deal with the IO part, so Low Code is usually very short as long as it focuses on the data itself.

### _Emily-Server_

- Only for license check and logs record.
  - There is no uploading skill itself.
    - If the server is to be landed, the environmental requirements are very low.

### _Mail Trigger_

- Send two mail at same time.
  - All work will be in a queue.
  - Would not loss any skills.

## **Second Skill**

### _User Insert_

- Let user input a number for Canvas present ~ months ago data.

### _Web Automation_

- The robot is trained using record, but it's very precise because Emily herself is also carved in Chromium.

### _Key in Username/Password by Text files_

- Simply key in can also be, Emily will be like a record of general web operations you key in the account password also as a step to record.
  - But it is relatively inflexible. Each user who downloads this skill can only log in with the account password you keyed in during training.

### _Write a simple CSV to Loop_

- Recieve mail addresses are written into CSV file to interate.

### _Send Email_

## **Conclusion**

### _Completely Automation_

### _Time Comsuming_

### _Any Question?_

## **Continue the possibility of extension**

### _Emily trigger Emily_

### _Other System trigger Emily_

# **_Other Notes_**

- Do not shake the cursor.
