<!-- Favicon: https://pingey.neocities.org/jinx.jpg -->
<!-- Title -->
Documentation
<!-- Table of Contents -->
- [Home](#)
- [Test](#/README)

<!-- Document Content -->

# Documentation

## Intro
ok first off, this is all modeled around the simple markdown files features, so its mechanically the same as other viewers, except this one is in a website, and has some extra features

## Tags
there are 4 tags currently,
- \<!\-\- Favicon: URL \-\-\>
- \<!\-\- Title \-\-\>
- \<!\-\- Table of Contents \-\-\>
- \<!\-\- Document Content \-\-\\>

first off, theres the Favicon tag, it changes the favicon url to any image, as long as the browser supports its fairgame
second off, title, i dont know why i didnt make this like the favicon tag but ehh, the title changes the header text and the tab title
third off, table of contents, its the menu on the left, right now, theres no way to make it so it jumps to a specific section of the document sadly
and lastly, document content, its basically the whole markdown file itself

## File system
the viewer has a simple file system to read markdown files:
### the url prefix
simply where to start 
> in this case its set to pingey.github.io/pingeytest
### the path
and the added path, to get the file, it adds .md to the end so make sure files are .md
> in this case its set to /doc.md
