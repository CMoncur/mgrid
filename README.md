# moncurgrid  
### The world's most lightweight CSS grid framework, designed to streamline front-end development  
  
## Overview  
Unlike other popular grid systems that can be split into 12 or more columns, the moncurgrid system focuses on only the most common divisions:  
- Quadrisections
- Trisections
- Bisections
- "Full Span"
  
### Quadrisections  
Quadrisections are divisions that are sized to be equal to one quarter of the container element.  Quadrisections are 220 pixels wide, with a 10 pixel margin.  An example of a quadrisection in use would look similar to this:  
	<div class="cf">
		<div class="quad">
			Lorem ipsum dolor sit amet
		</div>
		<div class="quad">
			Lorem ipsum dolor sit amet
		</div>
		<div class="quad">
			Lorem ipsum dolor sit amet
		</div>
		<div class="quad">
			Lorem ipsum dolor sit amet
		</div>
	</div>
  
### Trisections  
Trisections are divisions that are sized to be equal to one third of the container element.  Trisections are 300 pixels wide, with a 10 pixel margin.  An example of a trisection in use would look similar to this:  
	<div class="cf">
		<div class="tri">
			Lorem ipsum dolor sit amet
		</div>
		<div class="tri">
			Lorem ipsum dolor sit amet
		</div>
		<div class="tri">
			Lorem ipsum dolor sit amet
		</div>
	</div>
  
### Bisections  
Bisections are divisions that are sized to be equal to one half of the container element.  Bisections are 300 pixels wide, with a 10 pixel margin.  An example of a bisection in use would look similar to this:  
	<div class="cf">
		<div class="bi">
			Lorem ipsum dolor sit amet
		</div>
		<div class="bi">
			Lorem ipsum dolor sit amet
		</div>
	</div>
  
### Full Span  
Full spans are divisions that are sized to span the entirety of the container element.  Full spans are 940 pixels wide, with a 10 pixel margin.  An example of a full span in use would look similar to this:  
	<div class="cf">
		<div class="full">
			Lorem ipsum dolor sit amet
		</div>
	</div>
  
### Container Element  
The container element is a transparent divider that is 960 pixels wide.  The container element is designed to contain all gridded elements.  
  
### Clearfix  
Reviewing the code examples above, you might notice tags that look similar to this:
	<div class="cf">
This method is known as a "clearfix".  Clearfix is simply an exploit that forces a parent element to match the height of it's floated child elements.  The clearfix method is used to maintain the grid's structure and integrity.  
  
 ## Plugins  
 The moncurgrid system includes optional plugins to make other facets of CSS easy as pie.  Below are a list of optional plugins:  
 - Navigation
 - Typography
 - Forms  

### Implementation  
In order to use one or more of the aforementioned plugins, simply use one of the following methods:  
	<link rel="stylesheet" type="text/css" href="typography.css">
or
	@import url('typography.css');
  
### Navigation  
The navigation.css plugin is designed to streamline navigation style.  
  
### Typography  
The typography.css plugin is designed to streamline text style.  
  
### Forms  
As you might have guessed, the forms.css plugin is designed to streamline form style.  
  
## Browser Support  
The moncurgrid system is degisned to work on all major standards-compliant browsers (i.e. Chrome, Firefox, Opera, Safari).  moncurgrid also supports Internet Explorer versions 8 and later.
