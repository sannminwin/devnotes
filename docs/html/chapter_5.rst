
-------------------
HTML Input Types
-------------------
Here are the different input types you can use in HTML.

* ``<input type="button">``
* ``<input type="checkbox">``
* ``<input type="color">``
* ``<input type="date">``
* ``<input type="datetime-local">``
* ``<input type="email">``
* ``<input type="file">``
* ``<input type="hidden">``
* ``<input type="image">``
* ``<input type="month">``
* ``<input type="number">``
* ``<input type="password">``
* ``<input type="radio">``
* ``<input type="range">``
* ``<input type="reset">``
* ``<input type="search">``
* ``<input type="submit">``
* ``<input type="tel">``
* ``<input type="text">``
* ``<input type="time">``
* ``<input type="url">``
* ``<input type="week">``

Input Type Text
-------------------
``<input type="text">`` defines a **one-line text input field**.

Example:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

        <h2>Text field</h2>
            <p>The <strong>input type="text"</strong> defines a one-line text input field:</p>

            <form action="/action_page.php">

                First name:<br>
                <input type="text" name="firstname">
                <br>

                Last name:<br>
                <input type="text" name="lastname">
                <br>
                
                <input type="submit">

            </form>

            <p>Note that the form itself is not visible.</p>
            <p>Also note that the default width of a text field is 20 characters.</p>

        </body>
    </html>



Input Type Password
---------------------
``<input type="password">`` defines a **password field**.

.. code-block:: html
   :linenos:

    <form>
        User name:<br>
        <input type="text" name="username"><br>

        User password:<br>
        <input type="password" name="psw">
    </form>

.. note::   The characters in a password field are masked (shown as asterisks or circles).


Input Type Submit
----------------------
``<input type="submit">`` defines a button for **submitting** form data to a **form-handler**.
The form-handler is typically a server page with a script for processing input data.
The form-handler is specified in the form's ``action`` attribute.

Example:

.. code-block:: html
   :linenos:

    <form action="/action_page.php">

        First name:<br>
        <input type="text" name="firstname" value="Mickey"><br>

        Last name:<br>
        <input type="text" name="lastname" value="Mouse"><br>

        <input type="submit" value="Submit">

    </form>


Input Type Reset
--------------------
``<input type="reset">`` defines a **reset button** that will reset all form values to their default values.


.. code-block:: html
   :linenos:

    <form action="/action_page.php">

        First name:<br>
        <input type="text" name="firstname" value="Mickey"><br>

        Last name:<br>
        <input type="text" name="lastname" value="Mouse"><br>

        <input type="submit" value="Submit">

        <input type="reset">

    </form>

.. Note::   If you change the input values and then click the **Reset button**, 
            the form-data will be reset to the default values.



Input Type Radio
--------------------
``<input type="radio">`` defines a radio button.
Radio buttons let a user select ONLY ONE of a limited number of choices.


.. code-block:: html
   :linenos:

    <form>

        <input type="radio" name="gender" value="male" checked> Male<br>
        <input type="radio" name="gender" value="female"> Female<br>
        <input type="radio" name="gender" value="other"> Other

    </form>


Input Type Checkbox
--------------------
``<input type="checkbox">`` defines a **checkbox**.
Checkboxes let a user select ZERO or MORE options of a limited number of choices.


.. code-block:: html
   :linenos:

    <form>

        <input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
        <input type="checkbox" name="vehicle2" value="Car"> I have a car 

    </form>



Input Type Button
--------------------
``<input type="button">`` defines a button.


.. code-block:: html
   :linenos:

    <input type="button" onclick="alert('Hello World!')" value="Click Me!">



HTML5 Input Types
--------------------
HTML5 added several new input types:

* color
* date
* datetime-local
* email
* month
* number
* range
* search
* tel
* time
* url
* week

.. Note:: New input types that are not supported by older web browsers, will behave as <input type="text">.



.. code-block:: html
   :linenos:

    <form>

            <input type="color" name="favcolor">
            <br>

            Birthday:<br>
            <input type="date" name="bday">
            <br>

            Enter a date before 1980-01-01:<br>
            <input type="date" name="bday" max="1979-12-31">
            <br>

            Enter a date after 2000-01-01:<br>
            <input type="date" name="bday" min="2000-01-02">
            <br>

            Birthday (date and time):<br>
            <input type="datetime-local" name="bdaytime">
            <br>

            E-mail:<br>
            <input type="email" name="email">
            <br>

            Select a file:<br> 
            <input type="file" name="myFile">
            <br>

            Birthday (month and year):<br>
            <input type="month" name="bdaymonth">
            <br>

            Quantity (between 1 and 5):<br>
            <input type="number" name="quantity" min="1" max="5">
            <br>

            <input type="range" name="points" min="0" max="10">
            <br>

            Search Google:<br>
            <input type="search" name="googlesearch">
            <br>

            Telephone:<br>
            <input type="tel" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}">
            <br>

            Select a time:<br>
            <input type="time" name="usr_time">
            <br>
            
            Add your homepage:<br>
            <input type="url" name="homepage">
            <br>
    </form>



Input Restrictions
-------------------

Here is a list of some common input restrictions:

+---------------+-----------------------------------------------------------------------+
|   Attribute	|   Description                                                         |
+===============+=======================================================================+
|   disabled    |   Specifies that an input field should be disabled                    |
+---------------+-----------------------------------------------------------------------+
|   max         |   Specifies the maximum value for an input field                      |
+---------------+-----------------------------------------------------------------------+
|   maxlength   |	Specifies the maximum number of character for an input field    |
+---------------+-----------------------------------------------------------------------+
|   min         |   Specifies the minimum value for an input field                      |
+---------------+-----------------------------------------------------------------------+
|   pattern     |	Specifies a regular expression to check the input value against |
+---------------+-----------------------------------------------------------------------+
|   readonly	|   Specifies that an input field is read only (cannot be changed)      |
+---------------+-----------------------------------------------------------------------+
|   required	|   Specifies that an input field is required (must be filled out)      |
+---------------+-----------------------------------------------------------------------+
|   size        |   Specifies the width (in characters) of an input field               |
+---------------+-----------------------------------------------------------------------+
|   step        |   Specifies the legal number intervals for an input field             |
+---------------+-----------------------------------------------------------------------+
|   value       |   Specifies the default value for an input field                      |
+---------------+-----------------------------------------------------------------------+


The following example displays a numeric input field, where you can enter a value from 0 to 100, 
in steps of 10. The default value is 30:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

        <h2>Numeric Steps</h2>
        <p>Depending on browser support:<br>Fixed steps will apply in the input field.</p>

        <form action="/action_page.php">

            Quantity:
            <input type="number" 
                    name="quantity"
                    min="0" 
                    max="100" 
                    step="10" 
                    value="30"
            >

            <input type="submit">

        </form>

        <p>
            <b>Note:</b>type="number" is not supported in IE9 and earlier.
        </p>

        </body>
    </html>