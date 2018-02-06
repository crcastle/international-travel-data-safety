# Data Security When Traveling Abroad

Last updated: 2018 Feb 5

*Please help make this better! Submit changes [here](https://github.com/crcastle/international-travel-data-safety/pulls) and suggestions/comments [here](https://github.com/crcastle/international-travel-data-safety/issues).*

## Communication

### Texting

Note: *this includes SMS and other instant messaging like activities*

Services loosely ordered from more secure to less secure. In general, try to use one of the services near the top. Especially use them if you transmit passwords, PINs, social security numbers, bank account numbers, etc.

- **[Signal](https://signal.org/)**. Android, iPhone, and desktop apps. Messages are end-to-end encrypted. Free and open source code.
- **[WhatsApp](https://www.whatsapp.com/)**. Messages are end-to-end encrypted. WhatsApp implemented the same security that Signal uses, but it's not open source so you and I just have to take WhatsApp's word on this. Android, iPhone, Mac, Windows, Windows Phone, and web apps. WhatsApp is a great combination of ease of use + security -- e.g. I use it with all of my family, some being tech literate and some not.
- **[iMessage](https://support.apple.com/explore/messages)**. Apple says iMessage is encrypted end-to-end encrypted, but you or I cannot verify that. However, Apple has a lot to lose reputation-wise were someone to show that messages aren't encrypted, so I generally trust this service. Main downside is that it's not available to Android users.
- **[Telegram](https://telegram.org/)**. End-to-end encryption of messages is off by default but can be turned on. Android, iPhone, desktop, and web apps.

Services to avoid:

- **Regular SMS**. While 3G and above communication (i.e. including LTE) is encrypted between your phone and the tower, your SMS messages can be read by any cell service provider between the cell tower of your phone and the cell tower of the recipients phone.

### Voice/Video

- Most of the services listed above in "Texting" offer voice and video calls. Substitute Facetime in for iMessage.
- **Voice over a regular cell phone** calls should not be considered secure. Plus it's generally cheaper to make all voice and video calls using Signal/WhatsApp/Facetime than use the cell provider's voice service. However this depends on having internet wifi. Using the cell provider's data for voice or especially video can get expensive quickly.

### Email

- Generally assume that email is insecure. You should never share passwords, PINs, social security numbers, etc over email -- in the USA or anywhere. Bits of an email's path between your computer/phone and the recipient's computer/phone are secure, but there can be large chunks in the middle in which your email is floating around the internet as unencrypted plain text.
- **[ProtonMail](https://protonmail.com/)** is known to be the most secure way to send email. I've never used it, but would if I *had* to send something private via email. But first I would try to send using Signal, WhatsApp, or iMessage.

## Precautions for international air travel with devices containing sensitive data

This includes

- Phones
- Tablets
- Computers

### To do before traveling: Phones and tablets

- **iPhone**. iPhones are encrypted by default now. See [here for more info](https://ssd.eff.org/en/module/how-encrypt-your-iphone).
- **Android**. *to be written*
- **All**. Set a secure PIN or password to get in to the device. A 4 digit PIN is not secure. I recommend using at least 6 digits or a long word.

### To do before traveling: Computers

- **macOS**. Turn on [FileVault](https://support.apple.com/en-us/HT204837) or verify it's already on.
- **Windows**. Turn on [BitLocker](https://docs.microsoft.com/en-us/windows/windows-10/) or verify it's already on.
- **All**. Set a secure password for login to the machine. 8 characters or more is better. Throw some numbers and special characters in there if you can.

### To do while traveling: Phones

- **iPhone**. Before arriving at the airport, click the lock button five times to temporarily disable the TouchID or FaceID. [More info on why here](https://www.theverge.com/2017/8/17/16161758/ios-11-touch-id-disable-emergency-services-lock). Not sure if something like this exists for Android phones.
- Keep your sensitive data-containing devices with you at all times. Generally you have to let them go through a scanning machine briefly at security points, but I *never* check these devices.

## General tips

- Try not to use internet cafes. Well you can use them, but don't login to *anything*. They scare the crap out of me. You never know what's on that machine recording your keystrokes or if there's a camera watching you type, etc.
- Check your credit card statement for unknown transactions once a week or every few days while you travel and for a month after you get back.
- [This article](https://www.nomadicmatt.com/travel-blogs/data-security-for-travelers/) has some great additional tips, including
  - Turn on two-factor authentication for all your services. If your password is compromised, this could save you.
  - Avoid wifi networks with no password.
  - Do backups often, or make it easier and just keep your data on Dropbox, iCloud, or Google Drive.
- [Here's another useful article](https://lifehacker.com/how-to-keep-your-data-safe-when-traveling-abroad-1795545604), but it has some things that are a bit extreme like using a USB thumb drive computer and a burner phone.
