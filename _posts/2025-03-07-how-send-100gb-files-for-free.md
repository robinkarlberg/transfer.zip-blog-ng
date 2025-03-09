---
layout: post
title: "How to send 100GB files for free"
subtitle: "Introduction to Transfer.zip, a completely free way to send big files."
background: '/img/posts/01.jpg'
---

**Sending big files online can be tough.** Discord limits you to 25MB (now lowered to 10MB). Email can't handle big files. WeTransfer caps you at 3GB. Google Drive seems messy and invades privacy. 

## Finally, a solution:

### Send files free with no size limit using [Transfer.zip](https://transfer.zip/)

[Transfer.zip](https://transfer.zip/) lets you send files of any size, for free. It's open-source and on GitHub [here](https://github.com/robinkarlberg/transfer.zip-web). You can even host it yourself to ensure privacy. The official version uses the same verifiable code, ensuring safety.

Struggling to send large files? Try this! It's different and might be exactly what you need. The key feature is *Quick Share*. It sends files with no size limit. 

**Here's how it works:**

Quick Share uses WebRTC for peer-to-peer transfer. Files stream directly and aren't stored. No data is saved on Transfer.zip's servers. Files are encrypted using a client-side key, and data is safe even if traffic is intercepted. With direct peer-to-peer streaming, there are no size or bandwidth limits.

## How to use Quick Share

#### **1. Visit the site and choose your files**

Go to [Transfer.zip](https://transfer.zip/). Select your files or even a folder. The file name appears in a box once selected.

#### **2. Click send**

After choosing files, hit Send. A QR code and a shareable link appear. The link includes a unique file ID and an encryption key. Transfer.zip never sees the key.

![Screenshot of Quick Share showing a big QR code and that the user is waiting for someone to scan it](/img/quickshare.png)
*Screenshot of Quick Share*

#### **3. Scan the QR code or share the link**

Let others scan the QR code or send the link. Devices try to connect peer-to-peer. If blocked by firewalls, files relay through servers. They're still secure and encrypted.

#### **4. Wait during the transfer**

Once connected, transfers start. They're in real-time. If someone closes the browser, the transfer stops. This is a Quick Share limit but allows big file sizes. Speed depends on internet connections. Large files need patience!

#### **5. Done!**

Transfer complete! If issues arise, [report them on GitHub](https://github.com/robinkarlberg/transfer.zip-web/issues).
