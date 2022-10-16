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
