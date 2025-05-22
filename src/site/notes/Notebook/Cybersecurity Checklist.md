---
{"dg-publish":true,"permalink":"/notebook/cybersecurity-checklist/","tags":["computers/cybersecurity"],"created":"2025-05-06T19:19:50.344-06:00","updated":"2025-05-22T10:01:10.638-06:00"}
---

# Online Accounts

## Use a Password Manager

A password manager helps you create and store unique passwords for each online service you use. Having a unique password ensures that if one service is hacked, the compromised password won’t allow access to all of your other accounts.

At the very minimum, you should have a unique password for high-value accounts like your email and bank accounts.

Apps
• Bitwarden
• Proton pass
• KeePass

## Use Two-Factor Authentication

Two-factor authentication (2FA) adds an extra layer of security on top of passwords. It ensures that someone logging into an account is who they say they are by requiring an extra piece of information besides the account password.
This extra information is usually either "something you know", "something you have", or "something you are" — for example, a biometric signal like FaceID.

You should not use your phone number as a two-factor method.

At the minimum 2FA should be installed on accounts that allow access to other accounts: e.g. an email, Google, or Apple ID. For stronger security, ensure that 2FA is enabled on every service that supports it.

> [!NOTE]
> Using an all-in-one solution like Bitwarden for both password management and 2FA creates a single point of failure. Take this into account when picking your 2FA client. Be sure to back-up any recovery codes given to you during the 2FA setup process, otherwise you risk locking yourself out of your accounts.

Apps
• Aegis
• Bitwarden Authenticator
• Ente Auth
• Bitwarden
• Proton Pass
• KeePass

## Use a Privacy-First Email Provider

You should use an email provider that doesn’t read your email or gather data about your conversations to target you with ads.

Services
• Proton Mail
• Tutanota

# Web Browsing

## Use a Privacy-First Web Browser

You should use a web browser that protects you from tracking, fingerprinting, and unwanted advertisements.
Modern browsers have made it simple to transfer your bookmarks and preferences in order to reduce switching pains.

Apps
• Brave
• Firefox
• Librewolf
• Vivaldi
• Tor

## Use a Privacy-First Search Engine

You should use a search engine that protects you from tracking, fingerprinting, and unwanted advertisements. DuckDuckGo is a privacy-first search engine that does not store your search history, has strict location and personalization permissions, and publishes regular content teaching people how to be safer on the web.

Services
• Startpage
• DuckDuckGo
• Brave Search

# Mobile Devices

## Create a Strong Device Passcode

A four-digit passcode for your phone or other devices is no longer considered secure. You should use a six-digit passcode at the very minimum, and for extra security use a 12+ character passcode containing both numbers and letters. Biometrics, such as fingerprints and FaceID, should be disabled when traveling internationally, as they are not globally protected by law.

You should enforce a strict lock policy on your devices, such as auto-locking after five minutes or less. Always require a passcode immediately after waking the screen and ensure that your devices are not left unattended for more than a minute or two.

## Encrypt Your Devices

If your phone or computer is ever stolen, a thief may try to read or export your personal data. If your device is unencrypted, hackers will have access to everything stored on that device, including photos, emails, documents, and contacts.

You should enable encryption on every phone and computer you use. Encrypting your devices makes it nearly impossible for a thief to read your data without having your encryption password.

## Review Device Permissions

You should review all applications that have access to your files, camera, location, and microphone. Ensure that you trust apps with sensitive permissions.

## Keep Devices Updated

Many of the most damaging hacks in recent history were only possible because someone failed to update software. While update notifications delivered by your smartphone, computer, and other internet-connected devices can be disruptive, applying those updates in a timely manner is the single-most effective action you can take to protect yourself from these types of attacks.

You should apply software updates to every device you own as soon as they are made available, and develop a habit of checking for updates on devices that do not notify you of available patches to ensure their security.

# Network Connections

## Use Privacy-Friendly DNS Providers

DNS (Domain Name Servers) are the internet's equivalent of a phone book. They translate a name like 'google.com' into an IP address. By default, DNS is slow and insecure. Many internet service providers track and log data that flows through DNS, in some cases reselling this data to advertisers.

A good alternative to your ISP's default is Quad9 (9.9.9.9), which focuses on security and privacy in your everyday browsing. It's a non-profit founded by the Global Cyber Alliance, IBM, and Packet Clearing House, that blocks known malicious domains, and not collect any identifying data from users.

More feature-packed alternatives include Adguard and, my personal favorite, NextDNS. These providers allow you to create adblock lists at the DNS level, which is a very powerful implementation of adblocking. This method prevents any requests to ad domains from connecting, which speeds up network connections slightly.

## Enable DNS-over-TLS
Most modern devices have adopted a network security feature called DNS-over-TLS, or Private DNS in Android's case. This feature overwrites the default DNS provider of whatever network you are on with the one you specify. This allows greater control over your network communication, without needing any repetitive configuration on a per network basis.

# Social Media & Communication

## Remove Photo Metadata

Geotagging is the process of adding geographical identification to media files (photos and videos, for example). Anyone who has access to these tagged media files can read this data and learn where the photo was taken. Most social media sites strip the EXIF data from photos, but if you're hosting your own photos, be aware that the geolocation can give away your exact location.

You should understand how location metadata is attached to your media and take steps to ensure you are not uploading sensitive information with your files.

## Review Your Social Media Privacy Settings

Over the years social media companies are able to gather staggering amounts of data about you, your interests, who you talk to, where you go, what you buy, and so much more.

If you‘re not ready to give up social media quite yet, you should take the time to review your security and privacy settings. Visualizing the amount of information that social media companies know about you may be enough to curb that unhealthy newsfeed obsession.

## Use Encrypted Messaging Apps

When sharing sensitive information over chat, you should be using a secure, end-to-end encrypted messaging service. End-to-end encryption ensures that only you and your intended recipient are able to view messages. Your messages will appear scrambled (and will be nearly-impossible to unscramble) to anyone else, including app developers and ISPs.

Apps
• Signal
• Session
• Whatsapp
• iMessage

# Physical & Mental Protection

## Review the Privacy of Your Physical Space

You should add a webcam cover on your laptop and desktop computers. A webcam cover provides peace of mind when entering and exiting video calls that you are only visible when you choose to be.

You should protect yourself from people shoulder-surfing when working in a public space, such as a cafe or on a plane. A privacy screen blocks side views outside a 60 degree viewing angle.

## Educate Yourself About Phishing Attacks

Phishing is an attempt to obtain sensitive information (like an account password) by disguising as a trustworthy person or company. Phishing often occurs via email where a hacker will use social engineering to convince someone to click a link that goes to a fake login page. The fake login page then sends anything the victim types (including usernames and passwords) to the hacker.

In recent years phishing attacks have become increasingly sophisticated and hackers are learning to use data that people put on the web to create highly specific and targeted attacks.

Smart people are not immune to phishing.
You should learn the basics of phishing and how to identify a phishing attempt.