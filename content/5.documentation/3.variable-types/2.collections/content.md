Collections     {#intro}
===========
Stacey provides collections of related pages and assets which can be [looped over][] from within the templates.

**$root**
:   Will list each top-level page within _/content_.

**$children**
:   Will list any child pages relative to the current page.

**$parents**
:   Will list the full ancestor tree relative to the current page.

**$parent**
:   Will list the direct ancestor relative to the current page.

**$siblings**
:   Will list any pages sitting at the same level as the current page. This collection will also include the current page.

**$next_sibling**
:   Constructs a reference to the next page sitting at the same level as the current page (in reverse-numeric order).

**$previous_sibling**
:   Constructs a reference to the previous page sitting at the same level as the current page (in reverse-numeric order).

Asset Collections     {#asset-collections}
-----------------

**$images**<br>**$video**
:   Will output a list of all the images or video files associated with this page (ie. sitting in the same folder as the page’s .txt file). If there are no matching assets, these collections will be empty.

**$html**,<br>**$swf**,<br>**$mp3**,<br>**$pdf**,<br>etc.
:   Additionally, stacey will create a collection for any file type (other than .txt files) that it finds within the page’s folder.  
    Read more about [asset types][].

[looped over]: /documentation/editing-templates/templating-language/#language-contructs
[asset types]: /documentation/editing-templates/assets/#asset-types