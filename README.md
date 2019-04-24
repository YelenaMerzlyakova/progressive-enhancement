HTML
Some background info about the tags and attributes we use. 

Part One - Senmantic HTML


h1 - h6 = heading(s)
Represent headings and subheadings. These elements rank in importance according to the number in their name. The h1 element is said to have the highest rank, the h6 element has the lowest rank, and two elements with the same name have equal rank.

blockquote = a quote
The blockquote element represents a section that is quoted from another source.
Content inside a blockquote must be quoted from another source, whose address, if it has one, may be cited in the cite attribute.

q = quoted content
The q element represents some phrasing content quoted from another source.

img = image 
An img element represents an image. The image given by the src attribute is the embedded content, and the value of the alt attribute is the img element's fallback content.

p = paragraph 

The src attribute must be present, and must contain a valid non-empty URL potentially surrounded by spaces referencing a non-interactive, optionally animated, image resource that is neither paged nor scripted.

The img element must not be used as a layout tool. In particular, img elements should not be used to display transparent images, as they rarely convey meaning and rarely add anything useful to the document.

hr = horizontal rule = thematic break
Represents a paragraph-level thematic break. The "paragraph-level" bit means between blocks of text, so it can't be used to separate sections of a site. Instead, hr now separates different topics within a section of prose, or between scenes in a novel.

figure = fig(caption)
The figure element represents some flow content, optionally with a caption, that is self-contained and is typically referenced as a single unit from the main flow of the document.

The figure element can be used to annotate illustrations, diagrams, photos, code listings, etc., that are referenced in the main content of the document, but that could, without affecting the flow of the document, be moved away from that primary content — e.g., to the side of the page, to dedicated pages, or to an appendix.

caption =  
The caption element represents the title of the table that is its parent, if it has a parent and that is a table element.

When a table element is the only content in a figure element other than the figcaption, the caption element should be omitted in favor of the figcaption.

table = table
The table element represents data with more than one dimension, in the form of a table. Tables must not be used as layout aids.

th = table header
The th element represents a header cell in a table.

tr = table row
The tr element represents a row of cells in a table.

td = table data
The td element represents a data cell in a table.

ul = unordered list 
The ul element represents a list of items, where the order of the items is not important — that is, where changing the order would not materially change the meaning of the list.

ol = ordered list 
The ol element represents a list of items, where the items have been intentionally ordered, such that changing the order would change the meaning of the list.

li = list item
The li element represents a list item. If its parent element is an ol, ul, or menu element, then the element is an item of the parent element's list, as defined for those elements. Otherwise, the list item has no defined list-related relationship to any other li element.


Part two - Attributes

Adds the attribute Alt to the images. What is the purpose of this attribute?

If a device (browser) can not load an image you'll get description that is clarifies in the alt-tag. 

Adds a "good" or "bad" class to the tags surrounding the words "Good" and "Bad".
Find the link attribute to indicate the page to which the link should lead, and add it.
Make sure that when you click on the links, the page opens in a new browser tab. (you do this by using the target-attribute)
Find the attribute to display a small text box when hovering over links, like this ( you do this by using the title-attribute)