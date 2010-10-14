---
layout: article
uuid: 6cc5b302-7620-4122-be16-f6e4c2154a58
title: Learning About ID3 Tags
name: learning-about-id3-tags
created_at: 2010-10-13
updated_at: 2010-10-13
categories: id3
---

  I started learning about ID3 tags and the id3lib library looks like it can handle everything in the ID3 standard.  There are several versions of the ID3 standard, and I'm going to start with ID3V2.3.0 because that's what my mp3s use as their standard (and it should be pretty common).

  I set up the basic infrastructure of the ID3 to JSON program and I'll probably have a working version this week... if everything goes as planned.  I am already able to read out the data from text blocks, which means that all I really have to do is print out the ID3 standard name for the tag and then format it in JSON.  When that is complete, all I have to do is make sure taht it runs decently fast, and if it doesn't, then I need to decide whether I can optimize it in my code or whether I'll have ro rewrite the id3lib library (I hope that I don't have to do that because that would take a lot longer).

  So far the ID3 standard seems to support 74 unique tags, and id3lib supports 78 (I think those extra ones are left over from ID3V2.2 or something).  Anyway, onward and upward!!
