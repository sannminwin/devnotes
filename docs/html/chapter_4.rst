
-------------------
HTML Form elements
-------------------


The <input> Element
-------------------
The most important form element is the ``<input>`` element.
The ``<input>`` element can be displayed in several ways, depending on the type attribute.

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>HTML input Element</h2>

            <form action="/action_page.php">
                <input name="firstname" type="text">
            </form> 

            <br>
            <input type="submit">

        </body>
    </html>



The <select> Element
---------------------
The <select> element defines a **drop-down list**:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>HTML input Element</h2>

            <form action="/action_page.php">

                <select name="cars">
                    <option value="volvo">Volvo</option>
                    <option value="saab">Saab</option>
                    <option value="fiat">Fiat</option>
                    <option value="audi">Audi</option>
                </select>
                <br>
                <input type="submit">

            </form> 

        </body>
    </html>


.. note::   The ``<option>`` elements defines an option that can be selected.
            By default, the first item in the drop-down list is selected.
            To define a pre-selected option, add the selected attribute to the option.

Example:

.. code-block:: html
   :linenos:

    <option value="fiat" selected>Fiat</option>



.. note::   **Visible Values:**
            Use the ``size`` attribute to specify the number of visible values.

Example:

.. code-block:: html
   :linenos:

    <select name="cars" size="3">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
        <option value="fiat">Fiat</option>
        <option value="audi">Audi</option>
    </select>


.. note::   **Allow Multiple Selections:**
            Use the ``multiple`` attribute to allow the user to select more than one value.

Example:

.. code-block:: html
   :linenos:

    <select name="cars" size="4" multiple>
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
        <option value="fiat">Fiat</option>
        <option value="audi">Audi</option>
    </select>


The <textarea> Element
----------------------
The ``<textarea>`` element defines a multi-line input field **(a text area)**

Example:

.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>Textarea</h2>
            <p>The textarea element defines a multi-line input field.</p>

            <form action="/action_page.php">
                <textarea name="message" rows="10" cols="30">The cat was playing in the garden.</textarea>
                <br>
                <input type="submit">
            </form>

        </body>
    </html>

.. Note::   * The ``rows`` attribute specifies the visible number of lines in a text area.
            * The ``cols`` attribute specifies the visible width of a text area.



The <button> Element
--------------------
The ``<button>`` element defines a clickable **button**.


.. code-block:: html
   :linenos:

    <!DOCTYPE html>
    <html>
        <body>

            <h2>The button Element</h2>

            <button type="button" onclick="alert('Hello World!')">Click Me!</button>

        </body>
    </html>

.. Note::   Always specify the type attribute for the button element. 
            Different browsers may use different default types for the button element.