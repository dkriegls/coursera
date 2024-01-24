# Insturctions for completeing Lab 5 
## HTML Forms

**Objective:**

Create a valid HTML form that submits its data to the provided processing script. 

**Process:**
1. Using your text editor (i.e., Notepad++), create a new HTML file. Add your HTML skeleton. 
1. Create an HTML form that gathers the same info as the lab5-sample.pdf.
    * The lab5-sample.pdf shows the same form twice. Once with and once without the dropdown list showing.
    * You only have to create the form once. Don't duplicated the questions. 
1. Use the POST method for your form.
1. Use html “action” url: http://bloomingdale.sat.iit.edu/kriedan/lab3formscript.php
1. Use the following controls in your form.
    * Single line text fields
    * Multi line text area
    * Drop Down Menu
    * Radio Buttons
    * Checkboxes
    * Hidden field
    * Proper label tags on all the controls
    * Use the fieldset & legend on the form surrounding some controls where appropriate
1. In the hidden field I want the form to submit your name as its value.
1. Form processing script expects the controls to have exactly the following name attributes.
    * first_name_field
    * last_name_field
    * phone_field
    * email_field
    * comments_field
    * gender_field
    * available_field[] (*note the php array syntax [] to allow multiple values*)
    * age_field
    * hidden_field
1. Follow the video instructions for testing and turning in labs (*How to Turn In Labs*). 
1. Turn in the following:
    * Repo Link
    * Live Link
    * Image of Validation Screen Capture
    * Image of File Comparison
***
## You need to fully test the form and make sure it submits all the data properly before you turn in it.**
You will know if the form works properly if you see the results page and all the data you entered is correct. If I press submit and get an error, you can expect a very poor grade.
  


