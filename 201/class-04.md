## TEXT
#### Links are the defining feature of the web
##### because they allow you to move from one web page to another — enabling the very idea of browsing or surfing. You will commonly come across the following types of links:
● Links from one website to another
● Links from one page to another on the same website
● Links from one part of a web page to another part of the
same page
● Links that open in a new browser window
● Links that start up your email program and address a newemail to someone
## Writing Links
#### Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.
#### The text between the opening <a> tag and closing </a> tag is known as link text. Where possible, your link text should explain where visitors will be taken if they click on it (rather than just saying "click here"). Below you can see the link to IMDB that was created on the previous page.
##### Many people navigate websites by scanning the text for links. Clear link text can help visitors find what they want. This will give them a more positive impression of your site and may encourage them to visit it for longer. (It also helps people using screen reader software.)
#### To write good link text, you can think of words people might use when searching for the page that you are linking to. (For example, rather than write "places to stay" you could use something more specific such as "hotels in New York.")
## Linking to other sites
#### Links are created using the <a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link. Users can click on anything that appears between the opening <a> tag and the closing </a> tag and will be taken to the page specified in the href attribute. When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL. Browsers show links in blue with an underline by default.
## Linking to other PAges on the sAme site
#### When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL. If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file. If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page. You will learn more about these on the pages 81-84. If you look at the download code for each chapter, you will see that the index.html file contains links that use relative URLs.
### reLAtive urLs
#### Relative URLs help when building a site on your computer because you can create links between pages without having to set up your domain name or hosting. When linking to other pages within the same site, you can use relative URLs. These are like a shorthand version of absolute URLs because you do not need to specify the domain name. We will take a closer look at relative URLs on pages 83-84 as there are several helpful shortcuts you can use to write links to other pages on your own website.
## Layout
### In this chapter we are going to look at how to control where each element sits on a page and how to create attractive page layouts. This involves learning about how designing for a screen can be different to designing for other mediums (such as print). In this chapter we will:
● Explore different ways to position elements using normal
flow, relative positioning, absolute positioning and floats.
● Discover how various devices have different screen sizes
and resolution, and how this affects the design process.
● Learn the difference between fixed width and liquid layouts,and how they are created.
● Find out how designers use grids to make their pagedesigns look more professional.
## To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.) fixed Positioning This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page floating elements Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.
## sCreen sizes
#### Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
#### When designing for print, you always know the size of the piece of paper that your design will be printed on. However, when it comes to designing for the web, you are faced with the unique challenge that different users will have different sized screens. Since computers have been sold to the public, the size of screens has been steadily increasing. This means that some people viewing your site might have 13 inch monitors while others may have 27+ inch monitors. The size of a user's screen affects how big they can open their windows and how much of the page they will see. There are also an increasing number of handheld devices (mobile phones and tablets) that have smaller screens.
##### Judging the height that people are likely to see on the screen without scrolling down the page is much harder. For several years, designers assumed that users would see the top 570- 600 pixels of a page without having to scroll and some tried to fit all of the key messages in this area (fearing that people would not scroll down the page). As screen sizes have increased and handheld devices have become more popular, the area users will see is far more variable. The area of the page that users would see without scrolling was often referred as being “above the fold” (a term newspapers had originally coined to describe the area of the front page you would see if the paper were folded in half). It is now recognized that if someone is interested in the content of the page, they are likely to scroll down to see more. Having said which, usability studies have shown that visitors can judge a page in under a second so it is still important to let new visitors know that the site is relevant to them and their interests. As a result, many designs still try to let the user know what the site is about within the top 570- 600 pixels, as well as hint at more content below this point. But do not try to cram too much into that top area. Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).