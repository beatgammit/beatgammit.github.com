---
layout: article
uuid: 42cc32ca-53d0-4d89-8122-45dd7f0cf24d
title: Saving jpegs to file and starting github repo
name: saving-jpegs-to-file-and-starting-github-repo
created_at: 2010-10-20
updated_at: 2010-10-20
categories: id3
---
  Today I "finished" the library to turn id3 tags into JSON so that it is relatively usable.  It now outputs JSON for nearly every tag out there.  There are only a few non-standard tags that I don't output, but I think that's acceptable for now.  This means that this library now nearly 100% supports the id3 standard for mp3 tag names.  There are still a couple things to do, but that is lower on the totem pole than getting something usable out there.
  Right now, the jpegs are just being saved to disk, and I'm not entirely sure if it even works because I don't have any files to check it against.  I use the built in "ToFile" method, so everything should work smoothly.  I pushed everything to github, so I'm pretty excited about that.  Next up, getting something working for MPEG4 tags.  Woohoo!!
