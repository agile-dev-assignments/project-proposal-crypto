#Project Proposal: CopyPasta
Team Members: Adnan Rahat, Varun Bhardwaj, Lawrence Langman, Whitney Dankworth, Karan Tibriwal
#Overview:
Currently, users are unable to transfer clipboard data across multiple OS’s and devices. The workaround many individuals currently use is either emailing or messaging themselves with the content they want to transfer between platforms. Our idea is a cross-platform shared clipboard across all devices and ecosystems, similar to handoff within iOS. 
#For Whom: 
This software is designed for user’s who work with multiple OSs and are unable to transfer clipboard data. This includes iPhone users who have Windows OS running on their computer or Android users that have a Mac. Clearly, this is a mass consumer need for anyone using devices with an assortment of OSs. A stretch goal of Windows integration will also enable a seamless cross-platform experience for business users who often use iPhones and Windows devices in tandem.
#How:
A user has both an android device and an iOS device. The user copies a phone number from the android device, that text data is sent to Firebase Cloud Messaging and updates a queue of all previous copied text. That text can then be pasted on the iOS device. 
For future iterations, we want to allow for cross OS clipboard functionality within desktop apps for Mac and Windows as well.
#Scope: 
Clipboards already exist within platforms/ecosystems across devices. For example, it is a built-in function within Windows devices and is available in IOS. Since our project would be an extension of the existing software we believe the connection of these clipboards should be manageable. Additionally, connecting IOS & Android (Windows/Chrome app if time allows) seems an achievable goal since it is straightforward enough to complete yet generalized enough that we have room to expand the project given more time. Additionally, a GUI will be created for each platform we expand to, hence the need for this incremental approach.
