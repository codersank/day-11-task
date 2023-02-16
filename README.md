# day-11-task

3) Use certain HTML elements to display the following in a HTML page.

<!DOCTYPE html>
<html>
  <head>
    <title>Programming Languages and Frameworks</title>
  </head>
  <body>
    <h1>Programming Language</h1>
    <ul>
      <li>JavaScript</li>
      <li>Python</li>
      <li>Java</li>
    </ul>
    
    <h1>JavaScript Frameworks</h1>
    <ul>
      <li>Angular</li>
      <li>React</li>
      <li>Vue.js</li>
    </ul>
    
    <h1>Python Frameworks</h1>
    <ul>
      <li>Django Framework</li>
      <li>Flask Framework</li>
    </ul>
    
    <h1>Java Frameworks</h1>
    <ul>
      <li>Spring</li>
      <li>Maven</li>
      <li>Hibernate</li>
    </ul>
    
    <h1>Databases</h1>
    <ul>
      <li>MySQL</li>
      <li>MongoDB</li>
      <li>Cassandra</li>
    </ul>
  </body>
</html>

4) Design a contact us form with all fields as required.
<!DOCTYPE html>
<html>
  <head>
    <title>Contact Us Form</title>
  </head>
  <body>
    <h1>Contact Us</h1>
    <form method="post" action="submit-form.php">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="phone">Phone:</label>
      <input type="tel" id="phone" name="phone" required>
      
      <label for="subject">Subject:</label>
      <input type="text" id="subject" name="subject" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </body>
</html>


5)Create an element that helps you to open the https://google.com in separate new tab.
<a href="https://www.google.com" target="_blank">Open Google in a new tab</a>


6) In the form, add two radio buttons with grouping them for employee type(Salaried and own business)
<!DOCTYPE html>
<html>
  <head>
    <title>Contact Us Form</title>
  </head>
  <body>
    <h1>Contact Us</h1>
    <form method="post" action="submit-form.php">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="phone">Phone:</label>
      <input type="tel" id="phone" name="phone" required>
      
      <label for="subject">Subject:</label>
      <input type="text" id="subject" name="subject" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      
      <label>Employee Type:</label>
      <div>
        <label>
          <input type="radio" name="employee-type" value="salaried" required>
          Salaried
        </label>
        <label>
          <input type="radio" name="employee-type" value="business" required>
          Own Business
        </label>
      </div>
      
      <button type="submit">Send Message</button>
    </form>
  </body>
</html>





11) Create an HTML page, which should contain all types of input elements.

<!DOCTYPE html>
<html>
  <head>
    <title>HTML Form Input Elements</title>
  </head>
  <body>
    <h1>HTML Form Input Elements</h1>
    <form method="post" action="submit-form.php">
      <label for="text-input">Text Input:</label>
      <input type="text" id="text-input" name="text-input">
      
      <label for="password-input">Password Input:</label>
      <input type="password" id="password-input" name="password-input">
      
      <label for="email-input">Email Input:</label>
      <input type="email" id="email-input" name="email-input">
      
      <label for="tel-input">Telephone Input:</label>
      <input type="tel" id="tel-input" name="tel-input">
      
      <label for="number-input">Number Input:</label>
      <input type="number" id="number-input" name="number-input">
      
      <label for="date-input">Date Input:</label>
      <input type="date" id="date-input" name="date-input">
      
      <label for="time-input">Time Input:</label>
      <input type="time" id="time-input" name="time-input">
      
      <label for="datetime-local-input">Datetime-Local Input:</label>
      <input type="datetime-local" id="datetime-local-input" name="datetime-local-input">
      
      <label for="checkbox-input">Checkbox Input:</label>
      <input type="checkbox" id="checkbox-input" name="checkbox-input" value="1">
      
      <label for="radio-input-1">Radio Input 1:</label>
      <input type="radio" id="radio-input-1" name="radio-input" value="1">
      <label for="radio-input-2">Radio Input 2:</label>
      <input type="radio" id="radio-input-2" name="radio-input" value="2">
      
      <label for="select-input">Select Input:</label>
      <select id="select-input" name="select-input">
        <option value="option-1">Option 1</option>
        <option value="option-2">Option 2</option>
        <option value="option-3">Option 3</option>
      </select>
      
      <label for="textarea-input">Textarea Input:</label>
      <textarea id="textarea-input" name="textarea-input"></textarea>
      
      <button type="submit">Submit</button>
    </form>
  </body>
</html>

10) In your, HTML page add the below line and Highlight it without using any CSS.
"HTML & CSS is awesome"

<!DOCTYPE html>
<html>
  <head>
    <title>Highlight Text Example</title>
  </head>
  <body>
    <h1>Highlight Text Example</h1>
    <p>
      HTML &amp; CSS is <mark>awesome</mark>.
    </p>
  </body>
</html>



