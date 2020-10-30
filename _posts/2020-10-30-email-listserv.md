---
title: "So You Think You Know Email: Listservs"
date: 2020-10-30
author: "Steven Malins"
---

<img src="/assets/img/email01.jpg" style="width:100%;" />

In 1971 Ray Tomlinson invented email, or the story goes. 
The rest, as they say, is history. Despite the proliferation of books of faces, immediate grams, your spaces and my space, and whatever twitter is, much of online communication still happens by email, even in the year of Beyonce two thousand and twenty. 
I am willing to bet that more than %95 of you reading this have an email address; many of you likely have more than one! 
The ARPAMET that Ray Tomlinson used is different from our modern internet in important ways. 
Some will say it was a simpler time; much like walking everywhere was simpler before cars with internal combustion engines. 
But the basics of email that Ray hacked together are still in use.
We still use the 'at' sign to construct email addresses. 
Domain names have replaced individual server, or mainframe, names; but the second part of the email address still gives us a clue as to 'where' the user 'exists'
If someone has an email address that ends with '@ibm.com' they *probably* work for IBM, or at least do business with the company. 

Even though you probably checked your email before reading this very article, how much do you really know about how email works? For example, is the following a valid email address: 

> Abc\@def@twilighteve.com

Yep! The backslash escapes, or quotes, the first '@' character.
Check the RFC if you don't believe me! 

## What's a Listserv? 

Simply put a **listserv** is a server, or more correctly a program on a server, that mirrors mail sent to a common address to a *list* of addresses. 

For example, a simple lists might send any mail to *support@thecompany.com* to a group of support agents with email addresses *s.smith@thecompany/com*, *j.doe@thecompany.com*, and *supervisor@thecompany.com* 

That way, customers could have one email address to send issues to, but the email would be dealt with by whoever was on duty at the moment (or whoever checked their email first, or however else The Company(R) decided to handle it. 
Another common example is a newsletter mailing list, of which you are probably on several. 
A company puts a place holder address like *no-reply@shadymarketing.com* in the **to:** field and the mailing-list software sends the message to the list of their customer's email addresses. 
This has the advantage of being able to edit, add or subtract addresses, from the list in a centralized place.
Also, depending on the software, it hides the addresses of the other customers from customers that receive the email message; a good thing! 

In general, there are two types of mailing-lists:

1. **one way announce lists** that let administrators/authorized users send announcements and other messages to a list of addressees; but, which does *not* allow list members to send their own messages to the list. 
2. **discussion lists** which allow any member of the list to send a message to the list and have it forwarded to every other member on the list. 

Discussion lists allow for members of the list to exchange messages between one another; but the messages are **sent to every member of the list**.
Before online forums that allowed users to post messages on electronic "builtin boards" discussion lists allowed for group discussion of shared topics of interest. 
*Google Groups* is a very popular implementation of the discussion list concept, and is still going strong (for now!)
All legitimate discussion lists are **opt-in**.
That means members affirmatively choose to be a part of the group discussion. 
Discussion lists provide a number of advantages over similar methods. 
The primary one is that everyone, or almost everyone, already has email. 

Members can read and respond to messages using whatever software they currently use to read and write email messages. 
They can also set up their email client, such as Mozilla Thunderbird, to filter, or sort, the messages from the list into specific folders. 
That way they do not distract from the other email messages a user receives, but are in a convenient place when the user is ready to read messages from the list. 
Most discussion list software will change the subject of the messages and add the list name to the subject, making it easy to filter the messages.

For example, a list about canine feeding habits might add the string '[dogfood]' to the subject of all messages from/to the list. 
Most software also modifies the header of the messages. 
Headers are usually hidden from the user by most email software. 
But they help the whole system of email work, from fighting spam to filtering discussion list messages. 
Typically, the software will add a *List-Id:* header with a short description and domain name of the list. 

So what are you waiting for?
Go out and start joining some email discussion lists! 
Talk about your favorite sci-fi show. 
Or that research paper idea you have! 
