# 0Day Email Watcher (Grey Hack)
This repository contains a two-script setup for monitoring a 0Day email inbox in Grey Hack. The email checker logs into a target 0Day email account and prints the inbox contents, including the sender, subject, preview, and full message body. The watcher keeps the email checker running by automatically reopening it in a new Terminal whenever the email checker terminal is closed. This allows you to continuously refresh and re-check the inbox without manually relaunching the email script.

⚠️ IMPORTANT

Inside 0dayemail.src, the script must be compiled as 0dayemail. If the compiled name does not match, the watcher will not be able to relaunch the email checker correctly. The "0daywatcher.src" can be compiled under anyname seen fit.

You must also enter the email credentials inside 0dayemail.src:

// ---- config ----

day_email  = "ENTER_EMAIL"

day_passwd = "ENTER_PASSWORD"
