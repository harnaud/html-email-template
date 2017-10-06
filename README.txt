This is HTML Email template.
The purpose of this template is to write about anything you care about and send it as an email.
Example: Newsletter

Prerequisites:

- HTML basic knowledge
- CSS basic knowledge
- No JavaScript knowledge required

To work on this template, a web browser and a file editor are needed.
My favorite web browser is Chrome, Its developer tools offers a lot of functionalities.
As per the file editor, anything work.

Open the HTML file both with your web browser and your file editor.
A lot of back and forth between the file editor and the web browser to see the updates.
Press F5 when on your web browser to see the updates.

Attached is index.html file. This is the template. It's a HTML file as per its extension.
The idea is that each part of the page is a block.
The content of this template is customizable.

It's made of:
- header block   ('View this email in web browser' ... Facebook, Twitter, LinkedIn links)
- title	block	 (HTML Email)
- content block	 (blocks)
- footer block	 ('To unsubscribe, click here.' ... Copyright)


Blocks can be added/modified/deleted within the content block which is just a container.

Blocks are named with the following:
- 1C    [TITLE + TEXT WITHOUT PICTURE]
- 1C1P  [TITLE + CENTERED BIG PICTURE + TEXT]
- 2C1PR [2 COLUMNS TITLE + PICTURE ON THE RIGHT + TEXT ON THE LEFT]
- 2C1PL [2 COLUMNS TITLE + PICTURE ON THE LEFT + TEXT ON THE RIGHT]
- 2C2PT [2 COLUMNS TITLE + 2 PICTURES + TEXT]
- 2C2P  [2 COLUMNS TITLE + 2 PICTURES]
- 3C3PT [3 COLUMNS TITLE + 3 PICTURES + TEXT]
- 3C3P  [3 COLUMNS + 3 PICTURES]

Each block is customizable, leave the title blank if not needed.

CSS
For a HTML email, CSS is written inline with the HTML. (example <div style="">... </div>)
This is a very bad practice for a regular website where CSS should be written in <style> ... </style> tag or in a separate .css file.

For a HTML email, everything should be in one file and should be readable by any web browser.

Links:
<a href="http://www.google.com/search?q=pizza+chicago" style="text-decoration: none;">
	Click here to search pizza chicago on Google (this text is seen by the reader)
</a>

Images
Images can't be attached to the HTML email.
Images should be hosted on a 3rd party website (facebook, google+, ...)
Images can be referenced via their URL (example: http://www.google.com/image.jpg)

URL should be added to the src attribute of the img tag:
<img src="http://www.google.com/image.jpg" height="400" width="800" border="0" alt="Always have something here">
Src = source = URL of the image
height = height of the image in pixels
width = width of the image in pixels
alt = alternate title of the image when not found

Image size
For best performance, image should be as small as possible, but not too small. Resizing images is sometimes necessary.
Example: image where width = 300, resize to 300x225 and add an anchor around the image linking to the original image.
When reader clicks the image, he can see the bigger image in its original size
Example:
<a href="http://www.google.com/image_original.jpg" style="text-decoration: none;">
	<img src="http://www.google.com/image_300x225.jpg" width="300" border="0" alt="a picture">
</a>

Text
In this template, lorem ipsum is used as a placeholder, replace it with your text.

Colors
bgcolor="white" renders a white background
it works for a lot of colors (red, green, white, black, blue)
For more choice, RVB color codes should be used:
RGB (red, green, blue) in hex notation
bgcolor="#ffffff" renders a white background
bgcolor="#000000" renders a black background
See this website:
http://www.w3schools.com/cssref/css_colors.asp

Colors of the template can be changed. Feel free.

Special characters
Some characters are not supported by web browser natively.
Special characters should be replace with their ASCII value. See ASCII to special character table.
http://www.commentcamarche.net/contents/489-caracteres-speciaux-html

Comments
<!-- This is a comment, reader won't be able to see or read this -->