## June 22, 2019

## HTML&CSS by *Jon Duckett*

### Ch. 18, Process and Design

#### Brainstorm
Before you design site, ask "Who is my target audience?" Create fictional profiles of people visiting your site and think how will they view and interact with your site.
* Why are they coming? Look at motivations and goals
* Create a list of reasons **why** someone would come to site
* Look at each reason and decide how each person will achieve their goal
* Frequency. How often will someone visit and how often will you need to update content

#### Organization
* Create a site map w/ whiteboard
*  Keep visitor's goals in mind
* Wireframe: skeleton of your page with navigation bar and basic headings and body text
* Wireframe tool
  - [Mockingbird](http://gomockingbird.com)
  - [Lovely charts](http://lovelycharts.com)

#### Design Overview
* Make each part distinct from surrounding content
* Visual hierarchy: the order in which the eye sees content. Higher contrast is seen first
* Grouping related content
* Most users skim so focus on contrast using size, color, and style
* Images are great for contrast
* Each visual chunk can contains its own hierarchy
* Clear and concise Navigation bar

---------------------------------------------------------------------

#### Ch. 17, HTML5 Layout
(words in italics are tags that would appear in angle brackets with open and closed tag)
* *header* may contain the site name (h1) and navigation (nav)
* *footer* 
* *nav*
* *article*
* *aside*
* *section* groups related content together, may contain articles
* *hgroup* groups different sized headings so treated as one
* *figure* with *figcaption* contains content referenced from main flow of article, not just images
* *div* groups together related elements
* *a* you can turn and ENTIRE block into a link using 'a href=' and closing tag

---------------------------------------------------------------------

#### Ch. 8, Extra Markup
(words in italics are tags that would appear in angle brackets with open and closed tag)
* There have been many versions of HTML, so we begin our code with DOCTYPE to tell the browser which version the page is using
* *!-- comment goes here --* and will not be visible to user (but will be visible to anyone who looks at the source code so be mindful!)
* Attributes help when using CSS
  - id='blahblah'
  - class='hellohello'
  - example: *p id="pullquote"*
* Block elements always start on a new line 
  - *h1*
  - *p*
  - *ul*
  - *li*
* Inline elements always continue on the same line
  - *a*
  - *b*
  - *em*
  - *img*
* *span* is an inline eqivalent to *div*
* *iframe* meaning 'inline frame' is a little window cut into your page and inside that window you can see another html page! Great to embedd Google Maps into page. You need 3 attributes:
  - *width*
  - *height*
  - *src*
  You can also explore 3 others
  - *scrolling="no"* or *scrolling="yes"*
  - *frameborder="0"* means no border and *frameborder="1"* means yes border
  - *seamless*
* *meta* lives inside *head* and provides info not visible to user
* Make sure to use escape characters as needed


[Return to Homepage](README.md)