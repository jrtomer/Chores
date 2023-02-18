# Chores
- A csv (comma separated variables) file is read containing the chore schedule.
- After the file is read, the information is sorted based on chore, and week.
- A dictionary was created keying names to their phone numbers:
    **phone_dict['Jacob'] = "+14126604836"**
- The final function runs through everyone who is supposed to do chores that week and notifies them via a virtual phone number hosted by twilio.
   - The code is located on the master branch, not main.
   - Example: Sent from your Twilio trial account - Time to clean the KITCHEN Jacob
- **Only verfified numbers can receive messages via a twilio virtual phone number. That's why it's necessary that everyone verifies their number on twilio.** *It's free too.*


