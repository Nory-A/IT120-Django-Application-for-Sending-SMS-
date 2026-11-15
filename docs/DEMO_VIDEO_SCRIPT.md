# Demo video script (target: 5–7 minutes; allowed: 3–10)

**Before recording:** `.env` values are correct, the server is running, the Android phone with the TextBee app is online, and
you are *not* showing `.env`, the TextBee API-key page, or any password. Hide bookmarks/notifications. Close the editor tab
that holds `.env`. Check the final video length is between 3 and 10 minutes.

# Demo Video Script (Target: 5–7 minutes; Allowed: 3–10 minutes)

## Sample Script Flow

| Flow |
|---|
| **Introduction:** Briefly introduce the group activity on building a Django web application for sending SMS messages using Twilio. Explain that TextBee was used as an alternative. Discuss the project's purpose: to send SMS messages to a recipient's phone using TextBee (an Android phone gateway) through a Django web application. |
| **Application Demonstration:** Present the web application's user interface, including the Send SMS page (the reciepient phone number input and message input field). Demonstrating on entering an authorized test recipient's phone number and a sample message. Show the character counter, and message preview. |
| **Validation, Error Handling, Additional Features, and Testing:** Test an empty phone number, empty message, and invalid phone number (`90000`). Show the corresponding error messages. Demonstrate the SMS History page, message status refresh, statistics, and Contacts feature. |
| **SMS-Sending Process:** Demonstrate sending the SMS and briefly explain how the Django application communicates with the TextBee API. Show the success notification and the recipient's phone receiving the SMS. Explain that an accepted request does not automatically mean the SMS has been delivered. |
                                                                                 