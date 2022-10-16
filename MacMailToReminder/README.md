# Setup

Copy to: ~/Library/Application Scripts/com.apple.mail

```sh
cp MacMailToReminder/MailToReminder.scpt ~/Library/Application\ Scripts/com.apple.mail/MailToReminder.scpt
```

Customize by:

```sh
open /System/Applications/Utilities/Script\ Editor.app ~/Library/Application\ Scripts/com.apple.mail/MailToReminder.scpt
```

Go to Mail.

Open Preferences.

Select Rules.

Add a new rule and in the "Perform the following actions:" select "Run AppleScript" and then select your script and save.

# References

https://logic2design.blogspot.com/2022/02/MailmessagetoRemindersItemandTrelloCard.html

https://www.richardhyde.net/2019/04/16/New-Reminder-Using-JXA.html

https://github.com/moritzregnier/create-reminder-from-mail-mac/blob/master/EN.applescript

https://github.com/moritzregnier/create-reminder-from-mail-mac
