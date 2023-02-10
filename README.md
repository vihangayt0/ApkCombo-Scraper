## Search and get apk fron ApkCombo

- Author : [Vihanga-YT](https://github.com/vihangayt0)

***

## Example search
```js
const { 
search
} = require('apkcombo-scraper')

let search = await search('whatsapp')
console.log(search)
```
***
## OutPut
```js
[
  {
    name: 'WhatsApp APK',
    link: 'https://apkcombo.com/whatsapp/com.whatsapp'
  },
  {
    name: 'WhatsApp Business APK',
    link: 'https://apkcombo.com/whatsapp-business/com.whatsapp.w4b'
  },
  {
    name: 'WhatsApp Wallpaper APK',
    link: 'https://apkcombo.com/whatsapp-wallpaper/com.whatsapp.wallpaper'
  },
  {
    name: 'Telegram APK',
    link: 'https://apkcombo.com/telegram/org.telegram.messenger'
  },
  {
    name: 'AutoResponder for WhatsApp APK',
    link: 'https://apkcombo.com/autoresponder-for-whatsapp/tkstudio.autoresponderforwa'
  },
  {
    name: 'LINE APK',
    link: 'https://apkcombo.com/line/jp.naver.line.android'
  },
  {
    name: 'Messenger APK',
    link: 'https://apkcombo.com/facebook-messenger/com.facebook.orca'
  },
  {
    name: 'WhatsTool for Bulk WhatsApp APK',
    link: 'https://apkcombo.com/whatstool-for-bulk-whatsapp/com.whatstools.statussaver.directchat.trendingstatus.searchprofile'
  },
  {
    name: 'Wabi - Virtual Phone Number APK',
    link: 'https://apkcombo.com/wabi-virtual-phone-number/com.applaudsoft.wabi.virtual_number'
  },
  {
    name: 'Sticker Maker for WhatsApp APK',
    link: 'https://apkcombo.com/sticker-maker-for-whatsapp/stickermaker.stickercreater.whatsappstickers.stickermakerforwhatsapp'
  },
  {
    name: 'WhatAuto - Reply App APK',
    link: 'https://apkcombo.com/whatauto-reply-app/com.guibais.whatsauto'
  },
  {
    name: 'Informer: messages for Wear OS APK',
    link: 'https://apkcombo.com/informer-messages-for-wear-os/com.komparato.informer.wear'
  },
  {
    name: 'Sticker.ly APK',
    link: 'https://apkcombo.com/sticker-ly/com.snowcorp.stickerly.android'
  },
  {
    name: 'Facebook APK',
    link: 'https://apkcombo.com/facebook/com.facebook.katana'
  },
  {
    name: 'Viber APK',
    link: 'https://apkcombo.com/viber/com.viber.voip'
  },
  {
    name: 'Sticker maker APK',
    link: 'https://apkcombo.com/sticker-maker/com.marsvard.stickermakerforwhatsapp'
  },
  {
    name: 'Click to chat APK',
    link: 'https://apkcombo.com/click-to-chat/com.trianguloy.openInWhatsapp'
  },
  {
    name: 'Google Messages APK',
    link: 'https://apkcombo.com/google-messages/com.google.android.apps.messaging'
  },
  {
    name: 'Cool Chat Styler for Whatsapp APK',
    link: 'https://apkcombo.com/cool-chat-styler-for-whatsapp/com.cooltechngt.stylishchat'
  },
  {
    name: 'iCareFone Transfer to iPhone APK',
    link: 'https://apkcombo.com/icarefone-transfer-to-iphone/com.tenorshare.transfer'
  }
]
```
***

## Example dl
```js
const { 
dl
} = require('apkcombo-scraper')

let data = await dl('https://apkcombo.com/whatsapp/com.whatsapp')
console.log(data)
```
***
## OutPut
```js
{
  appname: 'WhatsApp',
  developer: 'WhatsApp LLC',
  mime: 'apk',
  id: 'com.whatsapp',
  description: '\n' +
    'WhatsApp from Meta is a FREE messaging and video calling app. It’s used by over 2B people in more than 180 countries. It’s simple, reliable, and private, so you can easily keep in touch with your friends and family. WhatsApp works across mobile and desktop even on slow connections, with no subscription fees*.\n' +
    '\n' +
    'Private messaging across the world\n' +
    '\n' +
    'Your personal messages and calls to friends and family are end-to-end encrypted. No one outside of your chats, not even WhatsApp, can read or listen to them.\n' +
    '\n' +
    'Simple and secure connections, right away\n' +
    '\n' +
    'All you need is your phone number, no user names or logins. You can quickly view your contacts who are on WhatsApp and start messaging.\n' +
    '\n' +
    'High quality voice and video calls\n' +
    '\n' +
    'Make secure video and voice calls with up to 8 people for free*. Your calls work across mobile devices using your phone’s Internet service, even on slow connections.\n' +
    '\n' +
    'Group chats to keep you in contact\n' +
    '\n' +
    'Stay in touch with your friends and family. End-to-end encrypted group chats let you share messages, photos, videos and documents across mobile and desktop.\n' +
    '\n' +
    'Stay connected in real time\n' +
    '\n' +
    'Share your location with only those in your individual or group chat, and stop sharing at any time. Or record a voice message to connect quickly.\n' +
    '\n' +
    'Share daily moments through Status\n' +
    '\n' +
    'Status allows you to share text, photos, video and GIF updates that disappear after 24 hours. You can choose to share status posts with all your contacts or just selected ones.\n' +
    '\n' +
    '\n' +
    '*Data charges may apply. Contact your provider for details.\n' +
    '\n' +
    '---------------------------------------------------------\n' +
    '\n' +
    'If you have any feedback or questions, please go to WhatsApp > Settings > Help > Contact Us \n',
  downloads: '5,000,000,000+',
  category: 'Communication',
  update: 'Feb 10, 2023',
  version: '2.23.3.74 (230374000)',
  img: 'https://play-lh.googleusercontent.com/bYtqbOcTYOlgc6gqZ2rwb8lptHuwlNE75zYJu6Bn076-hTmvd96HH-6v7S0YUAAJXoJN=s75-rw',
  size: '51 MB',
  link: 'https://download.apkcombo.com/com.whatsapp/WhatsApp_2.23.3.74_apkcombo.com.apk?ecp=Y29tLndoYXRzYXBwLzIuMjMuMy43NC8yMzAzNzQwMDAuOTViMjdlYzcwMDEzZjBhNDQ2MDRhOTY5ZDQ4ZTg4MThmZDg3YmFkYS5hcGs=&iat=1676043438&sig=434491761b7c94c025e6d44663aea391&size=53592420&from=cf&version=latest&lang=en&fp=945d4e52764ab9b1ce7a8fba0bb8d68d&ip=160.177.72.111'
}
```
***
