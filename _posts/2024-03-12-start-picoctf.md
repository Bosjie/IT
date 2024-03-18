---
title: "My first CTF event"
layout: single
classes: wide
author_profile: true
categories:
  - Cyber Security
tags:
  - CTF
---
Today I entered my first 'Capture The Flag' event at <a href="https://picoctf.org/" target="_blank">picoCTF</a> to see what CTF's are all about.
 
It's actually quite a lot of fun, learning about different topics in the process.

Let's see how far I can get with my current fundamental skills...

So far I LOVE the concept!

I'm brushing up my command line and networking skills in the meanwhile.

---

Some notes:
* priviledge escalation
* magic bytes https://www.garykessler.net/library/file_sigs.html
* forensics
* exiftool
* ADS (alternate data stream) in Windows
* hexdump
* hex editor
* disk analysis => use dd for copy of file
* dd if (input file) of(output file)
* dd if=/dev/sda \| gzip -c image.dd.gz (create disk image)
* disk analysis (image layers):
  - multimedia
  - block
  - journal
  - metadata
  - filename

* sleuthkit => traverse layers
* mmstat mmls (=> find start offset) mmcat (multimedia)
* blkstat blkls blkcat blkcalc (block)
* jls jcat ...
* istat (16274 (=inode)) ils icat ifind ...
* fls (-o 2048 (=offset)) fcat ffind ...
* Autopsy = Sleuthkit GUI

* Stegonagraphy (covered or concealed)
  - file format
  - LSB (least significant bit)
* cryptography (secret, hidden)
  - caesar (shift)
  - ciphertext
  - aes
  - rsa

* big endian / little endian (=reverse)
* steganalysis

