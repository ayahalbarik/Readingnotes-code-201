


# Website Layout
 website is often divided into headers, menus, content and a footer:
![website layout]( https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhhe6Zcx_tRytByVS6gKr7eMYKX9ctpFB8aA&usqp=CAU)

 * **layout parts** *
**Header**
A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name:

**Navigation Bar**
A navigation bar contains a list of links to help visitors navigating through your website

**Content**
The layout in this section, often depends on the target users. The most common layout is one (or combining them) of the following:

1-column (often used for mobile browsers)
2-column (often used for tablets and laptops)
3-column layout (only used for desktops)

**Footer**
The footer is placed at the bottom of your page. It often contains information like copyright and contact info

A website can be divided into various sections comprising of header, menus, content and footer based on which there are many different layout design available for developer. Different layouts can be created by using div tag and use CSS property to style it.

## Controlling the Position of Elements
1. position:static
2. position:relative
3. position:absolute
4. position:fixed
5. z-index
6. float


** Using Float to PlaceElements Side-by-Side
The clear property allows you
to say that no element (within
the same containing element)
should touch the left or righthand sides of a box. It can take
the following values:
1.clear
* right
* left
* both
* none 
2. Parents of Floated Elements: Solution
, developers have
opted for a purely CSS-based
solution because it means that there is no need to add an extra element to the HTML page after
the floated elements. The pure
CSS solution adds two CSS rules
to the containing element (in this
example the <div> element):
● The overflow property is
given a value auto.
● The width property is set to
100%.
3. Parents of FloatedElements: Problem
If a containing element only
contains floated elements, somebrowsers will treat it as if it is
zero pixels tall.
