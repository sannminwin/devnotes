
------------
HTML Form
------------


HTML <form>
-------------
The HTML <form> element defines a form that is used to collect user input:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>
            <h2>HTML Forms</h2>

            <form action="/action_page.php">
                
                First name: <br>
                <input type="text" name="firstname" value="Mickey"> <br>

                Last name:<br>
                <input type="text" name="lastname" value="Mouse"><br>

                <input type="submit" value="Submit">

            </form> 

            <p>
                If you click the "Submit" button, the form-data will be sent to a page called "/action_page.php".
            </p>

        </body>
    </html>


The <input> Element
-------------------
The <input> element is the most important form element.
The <input> element can be displayed in several ways, depending on the type attribute.

    Here are some examples:

    +------------------------+--------------------------------------------------------------+
    | Type                   | Description                                                  |  
    +========================+==============================================================+
    | <input type="text">    | Defines a one-line text input field                          |
    +------------------------+--------------------------------------------------------------+
    | <input type="radio">   | Defines a radio button (for selecting one of many choices)   |
    +------------------------+--------------------------------------------------------------+
    | <input type="submit">  | Defines a submit button (for submitting the form)            |
    +------------------------+--------------------------------------------------------------+


Text Input
^^^^^^^^^^
<input type="text"> defines a one-line input field for **text input**:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <head>
            <title> HTML text Input Element </title>
        </head>
        <body>

            <form>
                First name:<br>
                <input type="text" name="firstname"><br>
            
                Last name:<br>
                <input type="text" name="lastname">
            </form>

        </body>
    </html>



Radio Button Input
^^^^^^^^^^^^^^^^^^
<input type="radio"> defines a **radio button**.
Radio buttons let a user select ONE of a limited number of choices:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <head>
            <title> HTML Radio Button Input Element </title>
        </head>
        <body>

            <form>
                <input type="radio" name="gender" value="male" checked> Male<br>
                <input type="radio" name="gender" value="female"> Female<br>
                <input type="radio" name="gender" value="other"> Other
            </form>

        </body>
    </html>


The Submit Button
^^^^^^^^^^^^^^^^^
<input type="submit"> defines a button for **submitting** the form data to a **form-handler**.
The form-handler is typically a server page with a script for processing input data.
The form-handler is specified in the form's **action** attribute:


.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <head>
            <title> HTML Radio Button Input Element </title>
        </head>
        <body>

            <form action="/action_page.php">
                
                First name:<br>
                <input type="text" name="firstname" value="Mickey"><br>
                
                Last name:<br>
                <input type="text" name="lastname" value="Mouse"><br>

                <input type="submit" value="Submit">

            </form>

        </body>
    </html>
