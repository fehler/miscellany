Get Started With NFC
====================

*Estimated reading time: 5 minutes.*

**This content is a work-in-progress to include in my 2019-20 teaching at Belfast School of Art. I am new to Near Field Communication and I'm sharing what I've learned so far here. (I am by no means an expert.)**

The following is what I learned through the process of reading about and developing some projects for a Near Field Communication workshop. I'll be running this workshop for my [Interaction Design](https://www.ulster.ac.uk/courses/201920/interaction-design-15554) students this forthcoming academic year.

—[Christopher Murphy][00]



NFC Fundamentals
----------------

NFC (Near Field Communication) is **a set of communication protocols that enable two electronic devices** – one of which is usually a portable device, for example, a smartphone – **to establish communication by bringing them within ~four centimetres of each other**.

Unlike Bluetooth, **NFC doesn’t require any form of device discovery or manual pairing to transfer data**, which opens it up to multiple potential uses. With Near Field Communication **a connection is automatically triggered when another NFC device is in range**. Once in range, the two devices instantly communicate and send prompts to the user.

**You’ve probably used Near Field Communication already, if you’ve paid for something with a contactless reader,** if you’re using Apple Pay or Samsung Pay or a contactless credit card.

NFC tags are relatively inexpensive on Amazon, just [£7.50 for 10](https://amzn.to/2YcqAId), or [£26.99 for 50](https://amzn.to/2M6YU58). You can also buy them in a [card size](https://amzn.to/2K12MSM) for creating card-based projects.

**54p per tag (for 50) is a low enough cost to buy some NFC tags to experiment with.** Once you’ve decided how you’re going to use them, you can buy them in bulk. **You can also buy them in bulk, pre-programmed.**



NFC Uses
--------

NFC tags contain **a small unpowered NFC chip**. Depending on how the tag is programmed, an NFC tag can: **change various settings, launch apps and perform certain actions,** just by holding your smartphone close to it.

The tag takes a small amount of power from the phone and sends the information that's stored on it to the phone.

There are a range of different types of data you can program into an NFC tag, for example:

+ A URL: This could be a URL to a web page, or a URL for an app on Apple’s App Store or Google’s Play Store.

+ XXXX

+ YYYY 


Programming an NFC Tag
----------------------

**You can easily encode, erase, edit and lock an NFC tag in under a minute.** To do this, you just need to hover your phone over the tag and use an app to pass data to the tag.


### Apple

Unfortunately, Apple's iOS NFC SDK (Software Development Kit), Core NFC, [doesn't support writing NFC tags](https://help.gototags.com/article/writing-nfc-tags-ios/), only reading them. So, to program an NFC tag – until Apple updates Core NFC, which it's working on for iOS 13 – you'll need to use an Android device.

Apple has provided a useful overview of [Core NFC](https://developer.apple.com/documentation/corenfc), that's worth reading. They have also provided [sample code](https://docs-assets.developer.apple.com/published/9db0175572/CreatingNFCTagsFromYourIPhone.zip) for a project (iOS 13, Beta) that allows you to [create NFC tags from your iPhone](https://developer.apple.com/documentation/corenfc/creating_nfc_tags_from_your_iphone), saving data to tags and interacting with them using native tag protocols.

Unfortunately this is beta software, so – unless you’re running an iOS 13 Beta – you’ll need to wait for iOS 13’s stable release later in 2019. The good news is that native support is coming, albeit belatedly.

🎉


### Android

If you’re running an Android device, you can get started right away.

**Add instructions here.**



Example Projects
----------------

### Rich Business Card

One of my summer projects – preparing for my teaching in 2019-20 is the creation of a 'rich business card' that has data on it. It would be nice to have business cards that just said:

	[Mr Murphy ®](https://mrmurphy.com/contact/)

These cards would have an NFC tag on them that took you to my site, just by holding your phone near the card. Then I could give potential clients a business card that has all of my details programmed in.


### Educational Resource

Imagine being able to walk around an exhibition and be able to… etc., etc..

**Add instructions here.**



In Closing
----------

NFC looks interesting and it's something we could explore in a short workshop for #ixdbelfast, perhaps in the ‘Micro-Publications’ workshop. I'm working on workshop resources – this page is the start of this process – so that we can explore this in the forthcoming academic year.



About the Author
----------------

![Christopher Murphy](images/mr-murphy.png)

### Christopher Murphy

A designer, writer and speaker based in Belfast, [Christopher][13] mentors purpose-driven businesses, helping them to launch and thrive. He encourages small businesses to think big and he enables big businesses to think small.

As a design strategist he has worked with companies, large and small, to help drive innovation, drawing on his 25+ years of experience working with clients including: Adobe, EA and the BBC.

The author of numerous books, he is currently hard at work on his eighth, ‘Designing Delightful Experiences’, for Smashing Magazine and ninth, ‘Building Beautiful UIs’, for Adobe. Both are accompanied by a wealth of digital resources, and are drawn from Christopher’s 15+ years of experience as a design educator.


<!-- Links -->

[00]: https://github.com/fehler/miscellany/blob/master/get-started-with-nfc/get-started-with-nfc.md#about-the-author

<!--

trendblog have some useful information:

https://trendblog.net/creative-and-useful-ways-to-use-nfc-tags-with-your-smartphone/

https://trendblog.net/data-you-can-easily-program-on-nfc-tags/

https://trendblog.net/how-to-program-nfc-tags-with-your-android-device-video/

https://help.gototags.com/article/writing-nfc-tags-ios/

-->