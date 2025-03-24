# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration.
>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>My Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>
    
    <!-- External Image from Pexels -->
    <h2>Sample Image</h2>
    <img src="<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Simple Web Page</title>
    </head>
    <body>
        <!-- Ordered List with Roman Numerals -->
        <h2>My Ordered List</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
        </ol>
        
        <!-- External Image from Pexels -->
        <h2>Sample Image</h2>
        <img src="https://render.fineartamerica.com/images/images-profile-flow/400/images-medium-large-5/1-ferrari-599-gtb-douglas-pittman.jpg" alt="An image of acool ferari" width="500" height ="300">
        
        
        <!-- Simple Table -->
        <h2>Contact List</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>+123456789</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>+987654321</td>
                <td>jane@example.com</td>
            </tr>
        </table>
        
        <!-- Simple Registration Form -->
        <h2>Register Here</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <br><br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob">
            <br><br>
            
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <br><br>
            
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="kenya">Kenya</option>
                <option value="usa">Tanzania</option>
                <option value="Nigeria">Nigeria</option>
                <option value ="South Africa">Suth Africa</option>
            </select>
            <br><br>
            
            <input type="submit" value="Register">
        </form>
    </body>
    </html>
    
    <!-- Simple Table -->
    <h2>Contact List</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>+25412345670</td>
            <td>john@example.com</td>
            <
        </tr>
        <tr>
            <td>Jane Keen</td>
            <td>+254000000</td>
            <td>jane@example.com</td>
        </tr>
    </table>
    
    <!-- Simple Registration Form -->
    <h2>Register Here</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob">
        <br><br>
        
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="kenya">Kenya</option>
            <option value="Tanzania">Tanzania</option>
        </select>
        <br><br>
        
        <input type="submit" value="Register">
    </form>
</body>
</html>







