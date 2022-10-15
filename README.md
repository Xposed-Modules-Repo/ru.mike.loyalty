# Loyalty

Hide chats in the Telegram messenger

In the official Telegram messenger client Loyalty allows you to hide (and show again) chosen chats.

To show hidden chats tap the title several times.
To hide the chats back tap twice, turn off the screen or minimize the app. 
Your secret touches' sequence to show and events to hide chats are configured via the module's settings page.

## Install notes:
- install apk
- enable the module in your xposed manager app
- (for lsposed) select the Telegram app in the scope or - important! - uncheck and check it again if it's already selected
- reboot (in case of (Ed)xposed) or terminate the Telegram app (lsposed)
- select chats to hide, define the secret touches' sequence to show and the events to hide the chats back in the module's settings page
- test!

## Known behavior:
- if the secret touches' sequence is set, the chosen chats will always be hidden at the Telegram app startup (when it has not been launched before)
- to show the hidden chats the Telegram app will be restarted (this is a feature of the official client)
- the chats are hidden in the main screen, in the search screen (chats, media, links, files, etc.) and notification of them. Perhaps they can be visible somewhere else. If so, let me know

## Support/Discussion URL / Страница программы: 
[xda](https://forum.xda-developers.com/t/mod-xposed-4-1-loyalty-hide-chats-in-the-telegram-messenger.4505977/) or [4pda](https://4pda.to/forum/index.php?s=&showtopic=603033&view=findpost&p=118023452)

## Author
[MikeZh](https://4pda.to/forum/index.php?showuser=683427), 2022