AndroidSMSMessaging
===================

Work with sending and receiving text messages. Сreate an application that can send text messages to users based on their phone number. You will get contact information from the sqlite database created in previous classes. To register users into the db, you will use the register page you built in yesterday’s class.

<b>MainScreen:</b>
-  Contain two buttons
-  Button 1 “Register user” will load the RegisterActivity to the screen
-  Button 2 “Send Text” will load the ContactChooserActivity to the screen

<b>RegisterActivity:</b>
-  Will contain 4 text input fields for name, last name, age, phone number
-  Will contain a button. Once clicked the user information will be stored to a sqlite database (hopefully built in Monday’s class).

<b>ContactChooserActivity:</b>
-  Will contain a list. The list will be populated with the users from the sqlite database
-  Each list item should contain the name and phone number of one user
-  When a list item is clicked, the SendSMSActivity should be loaded
-  The phonenumber of the list item should be passed to the SendSMSActivity screen  

<b>SendSMSActivity:</b>
-  This screen will have two text field and one button
-  The textfields will be for the message body of the text and the phone number it will be sent to
-  The phone number textfield will be autopopulated based on the
-  Once the button is clicked the text will send to the phone number provided from the previous screen
