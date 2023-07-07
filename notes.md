## Markdown

headers are denoted by ##, you can make a big header using one hash and a small one using six hashes (min 1, max 6) 

a link text is denoted by square brackets, and the thing in the square bracket in the link text, and the URL you want displayed is in round brackets [anabelle's website](awcardoso.com)

to make text italic you use the underline symbol  _italic_ 

to make text bold you use stars *bold*

a codeblock in line is a back tick (underneath the tilda) 

a codeblock out of line is three back ticks 

open the file called `notes.txt` and then take notes

```
hello.this.is.code
for x in y
	hello
end
```


## HTML 

in html, everything is boxes. all websites are just boxes within boxes... so like the whole website is a box then the side bar is a box and the contact info at the bottom is a box etc etc 

to make things look a certain way in html, you wrap things in "tags"

to make a tag, you say `<tag> content inside the tag </tag>`

so this means make thing inside the tag apply the properties of the tag surrounding it 

`<h2>HTML</h2>`

like in markdown there are six headers (h1, h2, ... h6)

the most common tag in html is called div, this puts the content in the tag in a box 

at the beggining of each html document you first always see `<!DOCTYPE html>`

then, there are always three tags at the beginning: first, the one that encloses all the content on the whole page, this is `<html>`; this tag only ever has two children (boxes inside it), and these children are `<head> and <body>`; head contains all the metadata for the page, like the title of the page shown in tbar at the top and the icon that displays for the page is all in head; head is also where you load certain assets, like additional types of files athat aren't html, like style sheets and fonts; body contains all the actual content on the webpage, so everything that shows up on the page is here

to make a comment in html, you use <!-- comment --> 

every element (tag) has a class on it, classes are how you customise how an element looks

so for example you might have class="bold italic" 

`<tag class="nicetext 1">` 

another common tag is "a", which stands for anchor, and allows you to link to other websites/links within your website 

for example `<a href="awcardoso.com">anabelle's website</a>`

another common tag is "p", which stands for paragraph, and is like a div but makes space after certain lines, so if youre writing long paragraphs you can wrap them in p 

another useful one is the tag "img" for image; which works similar to "a", instead of href, you have a src (source) attribute which is where the image comes from 

`<img src="/link/file.jpeg">` (this tag doesnt need closing)

so to layout your boxes in a nice way and have it readable on phone and laptops (responsive design), you use twitter bootstrap, it also solves a lot of very common layout problems - like getting boxes exactly next to each other  

so to do that you just google twitter bootsrap and follow the quickstart instructinos to copy that stuff into thte stylesheet section of your code 

`<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">`

okay so if you are specifying how things change depending on your screen size, like phone ipad or laptop

so you say you want something to be 3 big on a laptop but 6 big on a phone screen 		

`<div class="col-6 col-md-4 col-lg-3"> </div>`

## Pushing changes

Okay so you edit your html file and you want to make your changes live, go and check the readme for instructions cool thank you 











