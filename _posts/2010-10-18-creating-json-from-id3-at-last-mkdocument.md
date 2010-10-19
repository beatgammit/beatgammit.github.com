---
layout: article
uuid: 24971ab3-9cb7-443b-9526-3a5ccc0aa2fd
title: Creating JSON from ID3, at last./mkdocument
name: creating-json-from-id3-at-last-mkdocument
created_at: 2010-10-18
updated_at: 2010-10-18
categories: id3
---
  I finally got my ID3 library to output JSON!! Woohoo!!  My code is not yet on github, but it finally works.  I still have a little cleaning up to do, and I might restructure the whole thing, but at least I have something working that gets all of the tags.  There are only a few things left to implement, namely binary output and the weird "NUMTYPES" field.  I am not sure what that is, but it should not be difficult to figure out.  I just really wanted to get some formatted JSON out the door.  I also need to figure out what to call the fields (I couldn't find any standards or naming conventions for them, but there are only 24 of them).
  My next step is to make sure that the code will work with ID3v1 tags as well, since they moved everything around when they moved to ID3v2, but the id3tag library claims to be able to handle it.  When I get everything working I'll push my code to github and perhaps document all of the frames/fields here on the blog.  Until then, onward and upward!
