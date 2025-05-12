# 3-assignment-and-projects
# html
<!DOCTYPE html> 
    <html>
        <head>
            <meta Author="Reagan Grandville" Year of publishing="2025">
            <title></title>

            <link rel="stylesheet" href="styles.css">
        </head>
<body>
    <header class="head-text1">
        <div class="head-text2">
            <h3>WELCOME TO 2025 HACKATHON</h3>
        </div>
    </header>
    <div class="container">
        <img src="hack.jpg" alt="hack 2025">
    </div>
    <div class="hackathon-info">
    <h2>About the Hackathon</h2>
    <p>
        Join us for the 2025 Hackathon, where innovators and developers come together to create groundbreaking solutions. 
        This virtual event will feature workshops, networking opportunities, and exciting challenges.
    </p>
</div>
    <div class="sidebar">
        <h4>Event Details</h4>
        <ul>
            <li>Date: May 15, 2025</li>
            <li>Location: Virtual</li>
            <li>Time: 10:00 AM - 5:00 PM</li>
        </ul>
        <button>Register Now</button>
    </div>
</body>
    </html>

#css
*{
    border: 0px;
    margin: 0px;
    padding: 0%;
}

body{
    background: black;
    
}

.head-text1 {
    color: greenyellow;
    padding: 20px; 
    padding-bottom: 5px; 
}



.head-text2{
    font-family: monospace;
    font-size: 30px;
    color: greenyellow;
    font-family: monospace;
    font-size: 30px;
}

.container {
    display: block;
    float: left;
    margin: 0; 
    padding: 15px; 
    width: 100%;
    border-radius: 50%; 
    width: auto; 
    height: auto; 
}


.hackathon-info {
    font-family: 'Montserrat', sans-serif;
    text-align: center; 
    color: white; 
    margin: 20px auto; 
    padding: 15px; 
    width: 60%; 
    background-color: #222; 
    border-radius: 10px; 
}

.hackathon-info h2 {
    font-size: 24px; 
    margin-bottom: 10px; 
    color: greenyellow; 
}

.hackathon-info p {
    font-size: 16px; 
    line-height: 1.6;
}

.container img {
    border-radius: 5%; 
    object-fit: cover; 
}

.container {
    float: left;
    width: 70%; 
}

.sidebar {
    float: right;
    width: 25%; 
    background-color: #333;
    color: white;
    padding: 15px;
    border-radius: 5px;
    text-align: left;
}

.sidebar h4 {
    margin-bottom: 10px;
    color: greenyellow;
}

.sidebar ul {
    list-style: none;
    padding: 0;
}

.sidebar ul li {
    margin-bottom: 5px;
}

.sidebar button {
    background-color: greenyellow;
    color: black;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
    border-radius: 5px;
}

.sidebar button:hover {
    background-color: limegreen;
}
