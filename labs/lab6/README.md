# Insturctions for completeing Lab 6 
## Styling Your HTML

**Objective:**

Take the css rules below and properly attach them to the html so that your index.html matches the image "*final_output*". 

**Process:**
1. Use the *index.html* file, the *css* folder, and the *images* folder to create your lab repository. Include the css and image files found inside the folders.
1. Open the image "*final_output*" and use that as a guide for styling.
1. Below are a series of CSS rules stacked in groups and a series of CSS selectors.
1. Your task, if you choose to accept it, is to figure out which CSS selector goes with which CSS rule stack in order to mimice the image "*final_output*".
1. Follow the video instructions for testing and turning in labs (*How to Turn In Labs*). 
1. Turn in the following:
    * Repo Link
    * Live Link
    * Image of Validation Screen Capture
    * Image of File Comparison

***

## CSS Selectors

1. body
1. #page-wrapper
1. #header
1. #header h1
1. #header a#logo1 img
1. #header #toplink
1. #footer
1. #content-wrapper
1. #main-content
1. h2 strong
1. .image-r
1. #side-content
1. #main-nav
1. #main-nav ul
1. #main-nav ul li
1. #main-nav ul li a
1. #main-nav ul li a:hover
1. #center
1. strong

***

## CSS Rule Stacks (You do not need to split up the chunks)
***
<!--This is one of very few situations where br is justified, a semantic break in the text. REMOVE the br in your final CSS -->

{ text-decoration: none;<br>
	position: absolute;<br>
	top:-34px;<br>
	right: 10px;<br>
	color: white;<br>
  font-size: 1.8em;}
***

{ margin-top: 20px;<br>
  margin-left: 20px;<br>
  margin-bottom: 20px;}
***

{	position: absolute;<br>
	left: 420px;<br>
	top:5px;<br>
  font-size: 3em;<br>
	font-family: 'Devonshire', cursive;<br>
  color: #E35335;}
***

{ position: relative;<br>
  margin-top: 40px;<br>
  border-radius: 12px 12px 0px 0px;}
***

{	background-color: #777;<br>
	height: 80px;<br>
	clear: both;}
***

{	list-style-type: none;<br>
	margin: 0;<br>
	padding: 0;<br>
	float: left;<br>
	position: relative;<br>
	left:50%;}
***

{	background-image: url("../images/repeating.png");<br>
	float: left;}
***

{	background-image: url("../images/black.jpg"); }
***

{	min-height: 300px;<br>
	width: 715px;<br>
	margin-right: 30px;<br>
	float: left;<br>
	margin-left: 15px;}
***

{ font-size: 2em;<br>
  font-weight: 900;}
***

{	float: right;<br>
	border: 2px solid blue;<br>
  width: 300px;<br>
	padding: 5px;<br>
	background-color: white;<br>
	margin: 10px 0 10px 20px;}
***

{	min-height: 150px;<br>
	width: 200px;<br>
	float: left;}
***

{	float: left;<br>
	width: 100%;<br>
	background-color: #333;}
***

{	padding: 10px 25px;<br>
	display: block;<br>
	text-decoration: none;<br>
	color: #ccc;}
***

{	background-color: #ccc;<br>
	color: #333;}
***

{	width: 960px;<br>
	margin: 0 auto;<br>
	box-shadow: 0px 4px 8px 2px rgba(0, 0, 0, 1);<br>
	border-radius: 12px 12px 0px 0px; }
***
  
{	float: left;<br>
	position: relative;<br>
	right: 50%;}