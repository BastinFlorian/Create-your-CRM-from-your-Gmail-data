# Create-your-CRM-from-your-Gmail-data
 
 From your gmail account, this scripts allows you to get some statistics about who and how often you are conversing with.
 For buisness developpers, it allows you to know which contacts you have from a specific company, their potential phone numbers and the   last date you contacted and received a message from them. It is very helpful to keep good relashionship with your clients.
 
 To launch this fonctionnality, you need to access to your Google Cloud Plateform console and create credentials that will allows the script to go in your email. Don't communicate this credentials. 

Step 1 : go to your GCP console and create a project </br>
Step 2 : enable gmail API </br>
Step 3 : create credentials using https://www.twilio.com/blog/2017/02/an-easy-way-to-read-and-write-to-a-google-spreadsheet-in-python.html </br>
Step 4 : save the credentials in the Data directory with the name "credentials.json" </br>
Step 5 : go to your google contacts in the Google contact section, click on other contacts, select all and export. Save this file as contacts.csv in the Data directory </br>
Step 6 : python main.py </br>
Step 7 : vizualize the output with potential phone numbers, frequency of the mail exchanges of each contact, last contact date, potential company of the contact 
