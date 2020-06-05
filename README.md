# Code_Refactor

## Description 

In this homework I refactor the html amd css codes for them to follow the accessibility standards and for the web-page to be optimized for search engines. I changed nd/or removed most of div tags in html file and replaced them with semantic tags in the places where it was possible, added alt attributes to all the pictures on the page and also changed the title for it to be more informative to the actual content.


## Changes in HTML file

First I changed text in titile from Website to Horiseon_Optimization_Strategies so the name of the page will be more informative and people could get the slight idea about the content.
I changed tag div with class header for a semantic tag header.
Then I changed the class=seo for id=seo because this is an only one place for such kind of change on the page.
The next change was I changed div tag before the list for nav tag because this is a navigation panel.
The next change was changing class=hero for the id=hero because it is also the one time case.
I added alt attribute to the hero picture.
Also I changed tag div class=content to semantic tag content.
Then I canged three div classes with images for semantic tags section. Also in this sections I changed the class attribute to an id attribute for the links in nav section to be able to bring you to the correct section. In the second and third sections I removed repeating attribues class.
I added alt attributes for three pictures in the section part.

The next part of the changes was for the aside part, so I changed div tag for semantic tag aside.
The other change was to make one class benefits instead of three classes benefit-lead, benefit-brand and benefit-cost because they represent basically the same things.
Added alt attributes for three pictures at aside part.
The other change was to change div tag footer for the semantic tag footer.
And the last change on the html document was to change h2 for h4 for the footer for the h elements to be in sequential order.


## Changes in CSS file

I changed selectors in the rule sets and declaration blocks for them to correlate with html document. Classes to be relate to classes, id-s to relate with id-s and semantic tags to relate with semantic tags.

The first rule set structures the whole page. I didn't change this one.
The next rule set sets background color of the whole page.

In the declaration block with header selection I changed it to relate with header semantic tag. 

The h1 rule sets how this part would look  - the size and line-block, as well as the seo property sets different color for the part of the h1.

The declaration block with nav attribute describes that navigation bar floats to the right and has certain fonts, margins and margins.

The li rule set also sets list style and margins for navigation part.

The a rule set also sets the color and text-decoration for the parts in navigation part.

The hero rule set sets how the background picture is placed, it's size, margins and it's source.

The content rule set describes the featuresof the content part and also there I changed it to correlate with semantic tag content and not the content class.

In the section declaration block I joined three classes.

Rule sets float-right and float-left are describing the position of the pictures in sections.

Rule sets h2 and p describes how the text part would look like in the section blocks.

Declarstion block aside joined three classes and described how the aside part would look like on the page and where it eould be placed.

The rule set benefits joined three classes in one and the h3 rule set describes the headers position and text align in the aside part.

The aside image rule set also joined 3 classes in one and describes how the images on the aside part would be placed.

The footer declaration block was changed to correlate with the footer semantic tag in html file and describes where  and how the footer part is placed on the page and how the text inside of it should look like.

The h4 attribute was changed because the headers should be in sequential order and it sets the font size of the header.

Also I organzed the rule sets and declaration blocks for them to be in the same order as the related eklements appear in the html file.



---
© 2020 Olena Turetska, student of th UCF Bootcamp. All Rights Reserved.

