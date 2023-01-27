# Authorized Version of the King James Bible 1611
## Downloaded the text version from **The Internet Archive**. 
This version is placed in the public domain and the formatting should lend itself to search and replace functions rather than hand editing the entire Bible.

wget https://archive.org/stream/TheHolyBiblekjv1611Wapocrypha/1611KjvW_apocrypha_djvu.txt

## Cloned the repository to local drive
cd to the directory where I want the repo to live
git clone git@github.com:OrthodoxFriar/King_James_Bible.git

## Take the text version and read it in to the <body> of an XHTML+RDFa document.
I have a template so I can `cat xhtml+rdfa.xml > King_James_Bible/AKJV.xhtml`

Now in Vim I can `:read ../AKJV.txt`
  
Now I realize my server isn't set up to sign commits so I will pause here to enforce signing.
