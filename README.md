Cisco IOS Scripts
=====

I've created this to help out all those students who find the formatting really annoying in the Academy PDF files :)


Collaborate with me!
---
Feel free to create a GitHub account and request to collaborate. The more scripts we get on here the better!

Simple Stuff
---

Reload your router once your done with your lab:

	en
	erase startup-config
	reload

Disable the annoying dns lookup:

	en
	config t
	no ip domain-lookup

Change hostname:

	en
	config t
	hostname mycoolhostname
