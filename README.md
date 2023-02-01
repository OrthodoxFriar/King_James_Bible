# Authorized Version of the King James Bible 1611
## The Goal
I want to take the text of the Authorized Version (KJV) and turn it into an XML document so that it can be parsed with XML tools. I'm starting with XHTML+RDFa so that it will render in a browser for live preview and because it will be trivial to turn it into an html document, just edit the !DOCTYPE definition at the top. I am documenting the steps here so that I can repeat them as needed.

## Downloaded the text version from **The Internet Archive**. 
This version is placed in the public domain and the formatting should lend itself to search and replace functions rather than hand editing the entire Bible.

`wget https://archive.org/stream/TheHolyBiblekjv1611Wapocrypha/1611KjvW_apocrypha_djvu.txt`

## Cloned the repository to local drive
cd to the directory where I want the repo to live
`git clone git@github.com:OrthodoxFriar/King_James_Bible.git`

## Take the text version and read it in to the <body> of an XHTML+RDFa document.
I have a template so I can `cat xhtml+rdfa.xml > King_James_Bible/AKJV.xhtml`

Now I realize my server isn't set up to sign commits so I will pause here to enforce signing.

## Why XML and why XHTML+RDFa?
First, the XHTML+RDFa can be changed to HTML by changing the first line to <!DOCTYPE html> although I would recommend HTML 4. Second, XML can be transformed into anything.
