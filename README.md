HTML5 Elements and Forms
<!DOCTYPE html>
<html>
<head>
    <title>HTML5 Elements and Forms</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>Python</li>
            <li>Web development</li>
            <li>Database</li>
            <li>Java Script</li>
        </ol>
    </section>

    <!-- External Image -->
    <section>
        <h2>External Image</h2>
        <img src="https://media.istockphoto.com/id/1386341272/photo/abstract-modern-tech-of-programming-code-screen-developer.jpg?b=1&s=612x612&w=0&k=20&c=cYeEgW6qwKRcTABFB715Eui2iF9OP-L5fSn6AsCMH08=" alt="Python Programming" width="300">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>Sophia Nakhanu</td>
                <td>243 Lang'ata</td>
                <td>+254798126282</td>
                <td>sophia.nakhanu1@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>035 Eldoret</td>
                <td>+271799126281</td>
                <td>janesmiith1@gmail.com</td>
            </tr>
            <tr>
                <td>Mike Johnson</td>
                <td>789 Luanda</td>
                <td>+45612378967</td>
                <td>mikejohnson@gmail.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>321 Paris</td>
                <td>+32198765432</td>
                <td>emilydavis2@gmail.com</td>
            </tr>
            <tr>
                <td>Robert Brown</td>
                <td>654 Cedar St</td>
                <td>+65432194387</td>
                <td>robertbrown@gmail.com</td>
            </tr>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br>

            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>
            <br>

            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select Country</option>
                <option value="Kenya">Kenya</option>
                <option value="UK">UK</option>
                <option value="Canada">Canada</option>
                <option value="Australia">Australia</option>
                <option value="USA">USA</option>
                <option value="Nigeria">Nigeria</option>
                <option value="Ghana">Ghana</option>
            </select>
            <br>

            <label>Interests:</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="cooking" name="interests" value="cooking">
            <label for="cooking">Cooking</label>
            <input type="checkbox" id="cycling" name="interests" value="cycling">
            <label for="cycling">Cycling</label>
            <br>

            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Multimedia Elements -->
    <section>
        <h2>Multimedia Elements</h2>
        <h3>Audio</h3>
        <audio controls>
            <source src="GOODBYE YESTERDAY  Elevation Rhythm & Gracie Binion_1739507710370.m4a.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <br>
        
        <h3>Video</h3>
        <video controls width="500">
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>
</body>
</html>
