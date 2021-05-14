# Welcome

Thank you for taking the time to Completing the paperwork.  *NOBODY* can go back and start a new **BEGINNING**, but *ANYONE* can start today and make a new **ENDING**.  I am looking forward to meeting you. Below are the things needed and directions to office.

### Photos/Scans

> 
Driver’s License     
Insurance Cards    
>    
 
### Forms
    
>
[Intake paperwork](http://google.com) 

[ROI](http://google.com) 
>    

### EAP

> 
Authorization number is needed when useing your employee assistance program.
> 

### Dean Counseling Inc.   
1337 E 17th Street   
Idaho Falls ID 83404      
Phone (208) 680-6488    
Fax (208) 202-2769   

**Located In Landmark Mental Health**

<!DOCTYPE html>
<html>

<body>

  <img src='https://s3-us-west-2.amazonaws.com/s.cdpn.io/2436099/formkeep%20275x92.png' alt='formkeep logo'>

  <h3>Sample Form Template | FormKeep</h3>
  <br>

  <form accept-charset="UTF-8" action="https://formkeep.com/f/exampletoken" method="POST" target="_blank" class="container">

    <!-- For detailed information check out these two sites
         https://www.w3schools.com/tags/att_input_type.asp
         https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Form_%3Cinput%3E_types
    -->

    <!-- type="text" A single-line text field. Line-breaks are automatically removed from the input value.
         placeholder="Your name..." is a great way to hint to the customer what kind of
         value you're expecting in the field and will not be submitted when they submit the form.
    -->
    <label for="name">Name</label>
    <input type="text" id="name" name="name" placeholder="John Smith"><br><br>

    <!-- type="email" a field for editing an e-mail address. -->
    <label for="email">Email</label>
    <input type="email" id="email" name="email" placeholder="john@example.com"><br><br>

    <!-- type="tel" on mobile devices will bring up a phone keyboard -->
    <label for="tel">Phone Number</label>
    <input type="tel" id="tel" name="tel" placeholder="555-123-4567"><br><br>   

    <!-- textarea is a multi-line plain-text editing control, useful when you want to 
         allow users to enter a sizeable amount of free-form text. 
     -->
    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Reason for contacting us" rows="5"></textarea><br><br>

    <!-- https://formkeep.com/guides/checkboxes-for-negative-or-multiple-answers
         By supplying a hidden "no" value with the same name as the checkbox, we will
         always get a "no" or "yes" value. Without that the subscribe value will not
         be sent if the field is unchecked.
    -->
    <input type="hidden" name="subscribe" value="no">
    <label for="checkbox"><input type="checkbox" id="checkbox" name="subscribe" value="yes" checked>Subscribe to our newsletter
    </label><br><br>

    <!-- force older browsers to submit your form data as UTF8. It helps ensure all submissions to your form will be encoded the same way.
         See https://intercom.help/formkeep/frequently-asked-questions/why-do-you-include-the-utf8-hidden-field-in-your-example-forms
    -->
    <input type="hidden" name="utf8" value="✓">

    <!-- There are certain names for common fields that browers will treat specially
        and autofill values for the user automatically. If you can use these names for
        your fields you should. See the url below for more detailed information about them
        https://html.spec.whatwg.org/multipage/form-control-infrastructure.html#autofill
          "name"
          "organization-title"
          "organization"
          "street-address"
          "address-line1"
          "address-line2"
          "address-line3"
          "address-level4"
          "address-level3"
          "address-level2"
          "address-level1"
          "country"
          "country-name"
          "email"
          "postal-code"
          "language"
          "bday"
          "bday-day"
          "bday-month"
          "bday-year"
          "sex"
          "tel"
          "tel-extension"
          "url"
    -->

    <button type="submit">Submit</button>
    <button type="reset">Clear Values</button>
  </form>

  <br><br><br><hr><br>
  <b><i>See information below for additional HTML elements you can cut and paste and incorporate into your form.</i></b>
  
  
  <h3>Extra Form Elements You Can Cut and Paste and Use</h3>
  
  
    <!-- type="radio" A radio button, allowing a single value to be selected out of multiple choices.
         give them all the same "name" to indicate which ones go together. You can use the 'checked'
         attribute to default a value when the form is loaded.
    -->
    <fieldset>
      <legend>Saluation</legend>
      <label><input type="radio" id="mr" value="mr" name="saluation">Mr</label>
      <label><input type="radio" id="mrs" value="mrs" name="saluation">Mrs</label>
      <label><input type="radio" id="ms" value="ms" name="saluation">Ms</label>
      <label><input type="radio" id="none" value="none" name="saluation" checked>None</label>
    </fieldset><br>
  
   <!-- datalist elements allow you to specify some values, but also allow them to type any value
        they'd like. the list="organization-title" and id="organization-title" need to match for this to
        work properly. The id="title" should be different than the id of the datalist.
    -->
    <label for="organization-title">Job Title</label>
    <input list="organization-title" id="title" name="title">
    <datalist id="organization-title">
      <option value="Manager">
      <option value="Product Manager">
      <option value="Engineer">
      <option value="Marketing Manager">
      <option value="Support Operations">
    </datalist><br><br>
  
    <!-- type="date" is a control for entering a date (year, month, and day, with no time). -->
    <label for="date">What day should we contact you?</label>
    <input type="date" id="date" name="date"><br><br>

    <!-- type="time" is a control for entering a time value with no time zone. -->
    <label for="time">What's the best time to contact you?</label>
    <input type="time" id="time" name="time"><br><br>

    <!-- type="url" is a field for entering a URL. example.com is a good placeholder for urls and emails -->
    <label for="url">What website can we help you with?</label>
    <input type="url" id="url" name="url" placeholder="https://example.com"><br><br>

    <!-- You can use a select element for the same purpose as a radio, for larger lists
      this is generally considered the better choice. You can use the 'selected'
      attribute to default a value when the form is loaded.
    -->
    <label for="country">Country</label>
    <select name="country">
      <option value="">Country...</option>
      <option value="BT">Bhutan</option>
      <option value="BL">Bonaire</option>
      <option value="BR">Brazil</option>
      <option value="CA">Canada</option>
      <option value="KY">Cayman Islands</option>
      <option value="CL">Chile</option>
      <option value="CN">China</option>
      <option value="FJ">Fiji</option>
      <option value="FI">Finland</option>
      <option value="FR">France</option>
      <option value="DE">Germany</option>
      <option value="GB">Great Britain</option>
      <option value="GR">Greece</option>
      <option value="IN">India</option>
      <option value="IT">Italy</option>
      <option value="JP">Japan</option>
      <option value="NZ">New Zealand</option>
      <option value="TW">Taiwan</option>
      <option value="GB">United Kingdom</option>
      <option value="US">United States of America</option>
    </select><br><br>
  
    <!-- type="number" is a control for entering a number. -->
    <label for="number">What is the overall budget for this project?</label>
    <input type="number" id="number" name="number"><br><br>

    <!-- https://formkeep.com/guides/checkboxes-for-negative-or-multiple-answers
         You can allow multiple selected values to the same name by adding a [] to the end of the name
    -->
    <fieldset>
      <legend>Check all that apply</legend>
      <label><input type="checkbox" name="help_needs[]" value="help_ux">UX Design</label><br>
      <label><input type="checkbox" name="help_needs[]" value="help_business">Business Process Design</label><br>
      <label><input type="checkbox" name="help_needs[]" value="help_backend">Backend Server</label><br>
      <label><input type="checkbox" name="help_needs[]" value="help_all">Full Product Developement</label><br>
    </fieldset><br>

    <!-- type="month" is a control for entering a month and year, with no time zone. -->
    <label for="month">Approximately when will this project be due?</label>
    <input type="month" id="month" name="month"><br><br>

    <!-- type="color" is a control for specifying a color. It will return the html hex color value -->
    <label for="color">What is the color theme for this project?</label>
    <input type="color" id="color" name="color"><br><br>

    <!-- type="range" is a control for entering a number whose exact value is not important.
         It displays a simple slider to allow the user to choose.
    -->
    <label for="range">How likely is it that you would recommend us to a friend or colleague?</label>
    <input type="range" id="range" name="range" min="0" max="10"><br><br>
  
</body>

</html>
