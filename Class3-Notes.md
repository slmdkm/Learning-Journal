February 2, 2017
Class Lecture

Global scope vs local scope

var x = 15;
Function foo() {
	console.log(‘I’m outside of bar:’, x);
	function bar () {
	var x =25:
	console.log (‘I’m am inside of bar: ‘,x)]}
bar();

Output
	foo()
	I am outside of bar: 15
I am inside of bar:25

Anonymous function
(function() {
	var x =10;
	x++
	console.log (x);……won’t run now
} ) ()………….calls it, ouput 11

•	returns provides output and stops executing, if we don’t type return, it will provide no output
•	returns are the very last thing inside a function

Images

•	Jpeg - High res, lots of color, lots of memory though, think about the users accessing your site, phones will not have a high band width capacity and will take forever to load
•	Png – transparent backgrounds, ie.octocat.png – you’ll see the gray checkered background, logos and fig? icons
•	Giffs – gray? Scale things, less common, no one wants a repeating giff on the page
•	Svg -Vector graphic can be modified using css, behind the scenes, every pixel is calculated as you go up and down, generally smaller files, as you scale up from 24px to 2000px, every pixel is getting calculated and maintains resolution, it’s awesome

Go into css
Image 100x100
Can go into css and type width 100px and height200px
	Element.style{
	width: 500px – this will auto increase height to 500px

width 100px will stretch across whole page

in dev tools – the image px will be in upper right hand corner

typically won’t use px, because on phone, it’s huge, on desktop its small, so use percentages

	element.style {
		width: 50%
}
	100% of my parent container
	50% will stay on 50% of page

max width and min width
		min width 50% - be at least 50% but can be more
<img src = “jpg” alt = “sad bear” style =” max-wideth: 50%”; title = “Broomstick”>

alt – means if pic isn’t there, sad bear will print next to a box
broomstick is a title in the picture

Johnduckngo site and books

Color

1)h1 {
	Color: blue; -define by name
}
2)p{
	color: #BADDAD – lime green – 0-9 and A-F, 16 values, will make a color, #000000 is black, #FFFFFF is white spectrum
	use style console in dev tools, click on color box and it will bring up color spectrum, the pen is a color picker, hover over pic and pick a color from image like if you want to match to picture

3) rgb colors
	color: rgb (255, 34, 45)       ---scale is 0 to 255
		(0, 255, 0) – the 255 is an all green color
	rgba(255, 0, 0, 1); alpha value …..0 to 1 …opacity.25 is really light
	opacity: applies to whole element, not just the text

4)hsla  
•	hue saturation lightness and alpha
•	0-360 all the way around the color wheel
•	hsl color picker or paletton.com – check this one out, randomize, then bottom right is visual simulation, export table and pick color list as html, css etc., select all, copy into css stylsheet
•	saturation – is gray
•	lightness –
•	a is opacity

how do you comfort a javascript bug, you console it….

•	Text – browsers have a default of 16px
•	Font-family – lists will pop up, these are available on browser but on our computer we have a library directory that has a font directory of all available fonts, so you can type in a font and it will pull from the list off the computer

•	Type in roboto font, but it’s not listed, it will default to another
•	Font-famil: roboto; fantasy; maybe one person’s computer has roboto, but another maynot and it will default to fantasy font

Import a font not found on computer – download a font file, SourceSansProBlack

•	@font-face is usually at the top of the style page
•
•	@font-face{
font-family: ‘SourceSansProBlack’;
src: url(fonts/SourceSansPro-Black.otf);
}

•	copy link from google fonts right above the link style in html, then go into css and put in font-family

•	network tag in console in dev tool
1 em is 16px
1.5 em
2em is 32px

1rem = equiv to font size of container element, body has font size of 24px, one rem is now 24px
1vw = viewport width, 1% of viewport width, 3vw, could use vh, but scott uses vw

•	non monospace – m takes up mspace and l takes up lspace, monospace all letters take up the same space

•	caniuse.com – website – tell you about browsers compatibility, if you are trying to reach to as much population as you can, this is a good app
•	TP mean technical preview
•	Majority of pop is on chrome and safari browsers

•	Size is important because you don’t want a click me add taking up all your space when you can utilize that space with your stuff.

•	Image editor – giff – don’s use the ones that ask to send finished copy in email. Check app store

Google fonts I liked: Gloria Hallelujah cursive, Barrio cursive, yatra one cursive, aladin cursive, engagement cursive, faster one cursive, metal mania cursive

<link href="https://fonts.googleapis.com/css?family=Metal+Mania" rel="stylesheet">

font-family: 'Metal Mania', cursive;


•	select keith’s file by accessing his username git hub, fork, under my account, clone, grab url, cd, git clone with the url space keith’s guesing game,

on my

button – top 10 favorite
address at bottome page

publish on web – create new branch and push to that branch
	git checkout –b gh-pages
		====switched to new
git push origin gh-pages

https://slmdkm/github.io/guessing_game(wahtever you named it)
https://<username>.github.io/<reponame>

on gh page, edit, the link will edited to the link name

lab for class 5

1)	array
2)	at the bottom are the functions, it will test the problems that we are going to write.
