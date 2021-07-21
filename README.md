# email_system_notification_java
java program completion of email_client project with email notifications added

***
Complete the email client project. Following functionalities will be evaluated in the viva. 

1. Continously check and retrieve new emails

2. Emails retrieved from the server should be converted into Email objects and serialized into the hard drive (each object should be serialized separately). 

3. Whenever an email is received, the email receiver should notify an EmailStatRecorder object and an EmailStatPrinter object. Upon receiving the notification from the email receiver, EmailStatRecorder prints the following message to the console "an email is received at <current time>". EmailStatPrinter prints the same message to a text file in the hard disk. The communication between the email receiver and EmailStatPrinter/EmailStatRecorder should be implemented using observer/observable concept. Email receiver should have only ONE list of observers.  NOTE: java 9 does not support observer/observable implementation, so have your own implementation - the one we discussed in the class. 

Move all the Java files into a single file and submit the text file.
 ***
