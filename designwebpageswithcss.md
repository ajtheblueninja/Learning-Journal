[Go to read me](/README.md)

# Design Webpages with CSS

First of all lets cover what CSS is, *css is a programing language* that lets you set rules that specify how the content of an element should appear, for example the background color, the colors of the lettering in a certain paragraph, to even the font of certain text boxes too. However it applys those rules to all of the elements that you assocate with that rule, meaning all if you make a rule about having all of the text be grey in the heading 1(h1) section then all the text you put in the h1 section will be grey and it only applys to the heading 1(h1) section if you say had text in a heading 2(h2) bellow the heading 1(h1) section well it wouldn't matter as the rules you set only affects the heading 1 section, but you can also sellect multiple sections to land under a certain rule. Meaning you can select heading 1(h1) and heading 2 (h2) to fall under a certain rule.

## More things about css

Css can br used to do more than just basic colors, it can be used to organize how your webpage looks or feels asthetically. It makes your page look impressive or presentable when done right but when done wrong it can make your webpage looks clumsy and rushed.

# The different types of css

Their are two types of cs, *Internal* and *External*, *External* css is used in the style file and thats used to style and set rules to make the page look a certain way. Internal css isn't to complicated and all you have to remember is what selector your choosing as depending on which one you choose your website may look different. *Internal* css is used to show pictures, videos, or other types of content like that. Those types are *link*, *href*, *type*, and *rel*. Now that may seem complicated but I'll break them down into easier bits to manage. *Link* is used in the html section to tell the browser where the internal css file is so it can give its look, its an emtpy element so it also doesn't need a closer and it lives inside of the head tag. *Href* refers to a path to the cs file, normally leading to the css style file. *Type* is a attribute that specifies the type of document being linked to. and finally the *Rel* which specifies the relationship between the html page and the file its linked to (normally relating to the css file which is also knows as the style file), its normaly value when used is stylesheet when linking to a css file.

## css selectors

Selectors are what helps determine whats affected by the rules that you make in the css style file, the types are *Universal selectors* which apply to all elements in the document, *Type selector* that matches elements names and then affects the matched names, *Class selectors* which match and element whose id has a value that matches the one after the noted thing, and those are the main 3 your mainly going to use but their are more like. *Child selectors* which matches an element that is direct child of another, *Descendant selectors* are used to match an element that is a descendant of another specified element, *Adjacent siblng selector* which matches an element that is the next sibbling of another, and finally *General sibling slector* which matches an element that is a sibling of another and it doesnt have to be directly preceding element

# css cascading rules and inheritance

If two or more rules apply to the same element, if they are identical the one that occurs last takes precedence over the other, and with rules if multiple clash the most specific rule takes precidence over the others. Inheritance is when you specify the font or color of a section like the body section, even if its in a smaller section inside of the body section it will be affected by the rule unless another is specified.