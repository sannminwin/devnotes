
-------------------
Basic HTML elements
-------------------


HTML Headings
-------------
A text header, denoted using the <h1>, <h2>, <h3>, <h4>, <h5>, <h6> tags.

.. code-block:: html
   :linenos:

   <!DOCTYPE html>
    <html>
        <title>My First Web Page</title>
            <body>

                <h1>Heading 1</h1>
                <h2>Heading 2</h2>
                <h3>Heading 3</h3>
                <h4>Heading 4</h4>
                <h5>Heading 5</h5>
                <h6>Heading 6</h6>

            </body>
    </html>


HTML Paragraphs
---------------
A paragraph, denoted using the <p> tag.

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <p>This is a paragraph.</p>
            <p>This is a paragraph.</p>
            <p>This is a paragraph.</p>

        </body>
    </html>


HTML Formatting Elements
------------------------

HTML uses elements like <b> and <i> for formatting output, like bold or italic text.
Formatting elements were designed to display special types of text:

    * <b> - Bold text
    * <strong> - Important text
    * <i> - Italic text
    * <em> - Emphasized text
    * <mark> - Marked text
    * <small> - Small text
    * <del> - Deleted text
    * <ins> - Inserted text
    * <sub> - Subscript text
    * <sup> - Superscript text


HTML Comment Tags
-----------------

You can add comments to your HTML source by using the following syntax


.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <!-- Write your comments here -->
            <!-- single line comment -->
            <!-- 
                multiline line comments
                1. create html
                2. add body tag and head tag
                3. add p tag
             -->

        </body>
    </html>


HTML Links
----------

HTML links are hyperlinks.
You can click on a link and jump to another document.

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>HTML Links</h2>
            <p>
                Visit linkedin profile to 
                <a href="https://www.linkedin.com/in/sannminwin/"> learn more </a>
                about the author.
            </p>

        </body>
    </html>

HTML Images
-----------

In HTML, images are defined with the <img> tag.
The <img> tag is empty, it contains attributes only, and does not have a closing tag.
The src attribute specifies the URL (web address) of the image.

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>Lorem Ipsum</h2>

            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                Nunc eu augue laoreet urna mollis tincidunt et a nisi. 
                Cras ante purus, egestas sit amet pellentesque eget, 
                ullamcorper nec turpis. Donec in nibh risus.
                of what the image contains:
            </p>

            <img 
                src="https://upload.wikimedia.org/wikipedia/commons/4/42/Aung_San_Suu_Kyi_17_November_2011.jpg" 
                alt="Daw Aung Sann Su Kyi" 
                width="206" 
                height="268"
            >

        </body>
    </html>


HTML Table
----------

An HTML table is defined with the <table> tag.
Each table row is defined with the <tr> tag. A table header is defined with the <th> tag. 
By default, table headings are bold and centered. A table data/cell is defined with the <td> tag.


.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>Lorem Ipsum</h2>

            <table style="width:100%">
                <tr>
                    <th>Firstname</th>
                    <th>Lastname</th> 
                    <th>Age</th>
                </tr>
                <tr>
                    <td>Jill</td>
                    <td>Smith</td>
                    <td>50</td>
                </tr>
                <tr>
                    <td>Eve</td>
                    <td>Jackson</td>
                    <td>94</td>
                </tr>
                <tr>
                    <td>John</td>
                    <td>Doe</td>
                    <td>80</td>
                </tr>
            </table>

        </body>
    </html>


Unordered HTML List
-------------------

An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
The list items will be marked with bullets (small black circles) by default.


.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>An unordered HTML list</h2>
            <ul>
                <li>Coffee</li>
                <li>Tea</li>
                <li>Milk</li>
            </ul>

        </body>
    </html>



Ordered HTML List
-------------------

An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
The list items will be marked with numbers by default.


.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>
        
            <h2>An unordered HTML list</h2>
            <ol>
                <li>Coffee</li>
                <li>Tea</li>
                <li>Milk</li>
            </ol>

        </body>
    </html>


HTML Block and Inline Elements
------------------------------
    Every HTML element has a default display value depending on what type of element it is. 
    The default display value for most elements is block or inline.


Block-level Elements
^^^^^^^^^^^^^^^^^^^^
A block-level element always starts on a new line and takes up the full width available 
(stretches out to the left and right as far as it can).
    

.. code-block:: html
    :linenos:

        <!DOCTYPE html>
        <html>
            <body>

                <div>Hello</div>
                <div>World</div>

                <p>The DIV element is a block element, and will start on a new line.</p>

            </body>
        </html>


Block level elements in HTML:

<address><article><aside><blockquote><canvas><dd><div><dl><dt><fieldset><figcaption>
<figure><footer><form><h1>-<h6><header><hr><li><main><nav><noscript><ol><p><pre>
<section><table><tfoot><ul><video>
    

Inline Elements
^^^^^^^^^^^^^^^^^^^^
An inline element does not start on a new line and only takes up as much width as necessary.
    

.. code-block:: html
    :linenos:

        <!DOCTYPE html>
        <html>
            <body>

                <span>Hello</span>
                <span>World</span>

                <p>The SPAN element is an inline element, and will not start on a new line.</p>

            </body>
        </html>


Inline elements in HTML:

<a><abbr><acronym><b><bdo><big><br><button><cite><code><dfn><em><i><img>
<input><kbd><label><map><object><output><q><samp><script><select><small>
<span><strong><sub><sup><textarea><time><tt><var>


HTML Attributes
---------------

Attributes provide additional information about HTML elements.
    * All HTML elements can have attributes
    * Attributes provide additional information about an element
    * Attributes are always specified in the start tag
    * Attributes usually come in name/value pairs like: name="value"


The href Attribute
^^^^^^^^^^^^^^^^^^
HTML links are defined with the <a> tag. The link address is specified in the href attribute.

..  code-block:: html
    :linenos:

        <!DOCTYPE html>
        <html>
            <body>

                <h2>The href Attribute</h2>
                <p>HTML links are defined with the a tag. The link address is specified 
                in the href attribute:</p>

                <a href="https://www.w3schools.com">This is a link</a>

            </body>
        </html>


The src Attribute
^^^^^^^^^^^^^^^^^^
HTML images are defined with the <img> tag.
The filename of the image source is specified in the src attribute.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body>

                <h2>The src Attribute</h2>
                <p>HTML images are defined with the img tag, and the filename of the image 
                source is specified in the src attribute:</p>

                <img src="img_girl.jpg" width="500" height="600">

            </body>
        </html>


The width and height Attributes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Images in HTML have a set of size attributes, which specifies the width and height of the image.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body>

                <h2>Size Attributes</h2>
                <p>Images in HTML have a set of size attributes, which specifies the width and 
                height of the image:</p>

                <img src="img_girl.jpg" width="500" height="600">

            </body>
        </html>


The alt Attribute
^^^^^^^^^^^^^^^^^
The alt attribute specifies an alternative text to be used, when an image cannot be displayed.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body>

                <h2>The alt Attribute</h2>
                <p>The alt attribute should reflect the image content, so users who cannot 
                see the image gets an understanding of what the image contains:</p>

                <img src="img_girl.jpg" alt="Girl with a jacket" width="500" height="600">

            </body>
        </html>


The HTML Style Attribute
------------------------

Setting the style of an HTML element, can be done with the style attribute.
The HTML style attribute has the following syntax.

::

    <tagname style="property:value;">



HTML Background Color
^^^^^^^^^^^^^^^^^^^^^
The background-color property defines the background color for an HTML element.
This example sets the background color for a page to powderblue.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body style="background-color:powderblue;">

                <h1>This is a heading</h1>
                <p>This is a paragraph.</p>

            </body>
        </html>


HTML Text Color
^^^^^^^^^^^^^^^
The color property defines the text color for an HTML element.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body style="background-color:powderblue;">

                <h1 style="color:blue;">This is a heading</h1>
                <p style="color:red;">This is a paragraph.</p>

            </body>
        </html>


HTML Fonts
^^^^^^^^^^
The font-family property defines the font to be used for an HTML element.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body style="background-color:powderblue;">

                <h1 style="font-family:verdana;">This is a heading</h1>
                <p style="font-family:courier;">This is a paragraph.</p>

            </body>
        </html>



HTML Text Size
^^^^^^^^^^^^^^
The font-size property defines the text size for an HTML element.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body style="background-color:powderblue;">

                <h1 style="font-size:300%;">This is a heading</h1>
                <p style="font-size:32px;">This is a paragraph.</p>

            </body>
        </html>


HTML Text Alignment
^^^^^^^^^^^^^^^^^^^
The text-align property defines the horizontal text alignment for an HTML element.

..  code-block:: html
    :linenos:
    
        <!DOCTYPE html>
        <html>
            <body style="background-color:powderblue;">

                <h1 style="text-align:center;">Centered Heading</h1>
                <p style="text-align:center;">Centered paragraph.</p>

            </body>
        </html>



Complete list of CSS properties:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

https://www.w3schools.com/cssref/


Exercises
---------
    1. Create a webpage that prints your todo list to the screen.
    2. Create a webpage that prints short biography of the person you admired most.
    3. Create a webpage that prints a table of your weekly expense (date, title, cost).

