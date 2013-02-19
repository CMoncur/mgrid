# mgrid  
### The world's most lightweight CSS grid framework, designed to streamline front-end development  
  
## Preface
mgrid is designed to be a simple and easily implemented starting point for web projects large and small.  It promotes CSS best practices, minimizes redundancy, and will allow a project to scale.  mgrid will not be for everyone, as it is not quite as flexible as popular alternatives such as the 960 grid system.  However, for an overwhelming majority of grid-based web projects, mgrid is a perfect fit.  In fact, the site designs of the most popular grid systems (960.gs, 978.gs, blueprintcss.org, etc...) could have been implemented easier using mgrid as opposed to the grid system advertised.  
  
### Ready to get started?
Here is an extensive list of things you'll need before using mgrid:  
- A computer
- A fundamental understanding of CSS
  
## Overview
Unlike other popular grid systems that can be split into 12 or more columns, the mgrid system focuses on only the most common divisions:  
- Quadrisections
- Trisections
- Bisections
- "Full Span"  
  
### Quadrisections  
Quadrisections are divisions that are sized to be equal to one quarter of the container element.  Quadrisections are 220 pixels wide, with a 10 pixel margin.  An example of a quadrisection in use would look similar to this:  
```
<div class="content">
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
```
  
### Trisections  
Trisections are divisions that are sized to be equal to one third of the container element.  Trisections are 300 pixels wide, with a 10 pixel margin.  An example of a trisection in use would look similar to this:  
```
<div class="content">
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
```
  
### Bisections  
Bisections are divisions that are sized to be equal to one half of the container element.  Bisections are 460 pixels wide, with a 10 pixel margin.  An example of a bisection in use would look similar to this:  
```
<div class="content">
	<div class="bi">
		Lorem ipsum dolor sit amet
	</div>
	<div class="bi">
		Lorem ipsum dolor sit amet
	</div>
</div>
```
  
### Full Span  
Full spans are divisions that are sized to span the entirety of the container element.  Full spans are 940 pixels wide, with a 10 pixel margin.  An example of a full span in use would look similar to this:  
```
<div class="content">
	<div class="full">
		Lorem ipsum dolor sit amet
	</div>
</div>
```
  
### Container Element
The container element is a transparent divider that is 960 pixels wide.  The container element is designed to contain all gridded elements.  
   
### Clearfix  
Reviewing the code examples above, you might notice tags that look similar to this:
```<div class="content">```
These elements are "clearfixed".  A clearfix is simply an exploit that forces a parent element to match the height of it's floated child elements.  The clearfix method is used to maintain the grid's structural integrity.  
  
## Plugins
The mgrid system includes optional plugins to make other facets of CSS easy as pie.  Below are a list of optional plugins:  
- Navigation
- Typography
- Forms  

### Implementation  
In order to use one or more of the aforementioned plugins, simply use one of the following methods:  
```
<link rel="stylesheet" type="text/css" href="typography.css">
```
or
```
@import url('typography.css');
```
  
### Navigation
The navigation.css plugin is designed to streamline navigation style.  
  
### Typography
The typography.css plugin is designed to streamline text style.  
  
### Forms
As you might have guessed, the forms.css plugin is designed to streamline form style.  
  
## Browser Support
The mgrid system is degisned to work on all major standards-compliant browsers (i.e. Chrome, Firefox, Opera, Safari).  mgrid also supports Internet Explorer versions 8 and later.  

## License
mgrid is licensed under MIT and GPL.  
Copyright (c) 2013 Cody Moncur
