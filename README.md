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
- Add a registration form

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
<html>
    <head>
        <title></title>
        <body>
            <ul>
                <li>Join us</li>
                <li>Connect with us</li>
                <li>Become our member</li>
                <br><br>
    <form action="" method="">
                <fieldset>
                    <legend>Personal Information</legend>
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required placeholder="Enter your name">
                <br><br>
                <label for="Id_number">ID Number:</label>
                <input type="text" id="Id_Number" name="Id_Number" required>
                <br><br>
                <label for="adress">Adress:</label>
                <input type="text" id="adress" name="adress" required>
                <br><br>
                <label for =email>Email:</label>
                <input type="email" id="email"name="email" required>
                <br><br>
                <label for="password">Password:</label>
                <input type="text" name="password" required>
                <br><br>
                <label>Gender:</label>
                <input type="radio" value="male">male
                
                <input type="radio" value="female">female
                <br><br>
                <button type="submit">Submit</button>
                <button type="Reset">Reset</button>
                <br><br>
                <label for="School">School:
                </label>
                <select name="School" id="School">
                    <option>--Select school--</option>
                    <option value="Ranjira">Ranjira</option>
                    <option value="Okanaa">Okana</option>
                    <option value="Life water">Life water</option>
                    <option value="Bungu">Bungu</option>
                    <br><br><br><br>

                    <label for="category">Categories:</label>
                    <input type="checkbox" name="category" value="Primary">Primary
                    <input type="checkbox" name="category" value="Junior secondary">Junior secondary
                    <input type="checkbox" name="category" value="Senior secondary">Senior secondary
                    <br><br>


                </select>
                </fieldset>
            </form>
            <table border="2">
                <thead>
                    <tr>
                        <th>First Name</th>
                        <th>Last Name</th>
                        <th>Course</th>
                    </tr>

                </thead>
                <tbody>
                    <tr>
                        <td>Alex</td>
                        <td>Mathenge</td>
                        <td>Software engineering</td>
                    </tr>
                    <tr>
                        <td>David</td>
                        <td>Ouma</td>
                        <td>Bcom</td>
                    </tr>
                    <tr>
                        <td>Fabisch</td>
                        <td>Onyango</td>
                        <td>BIT</td>
                    </tr>

                </tbody>
                <tfoot>
                    <tr>
                        <th>First Name</th>
                        <th>Last Name</th>
                        <th>Course</th>
                    </tr>

                </tfoot>
            </table>
            <audio controls>
                <source=03 Winy Duond Yesu.mp3 type="audio/mpeg">
            </audio>
        </body>
    </head>
</html>
