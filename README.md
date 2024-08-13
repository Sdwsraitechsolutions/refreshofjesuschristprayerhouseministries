<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Refreshment of Jesus Christ Prayer Home Ministries</title>
    <link rel="stylesheet" href="sdwjr.css">
    <link rel="stylesheet" href="contact.html">
    <link rel="stylesheet" href="churchhistory.html">
    <link rel="stylesheet" href="ministries.html">
    <link rel="stylesheet" href="servicetime.html">
    <link rel="stylesheet" href="sermon.html">
    <link rel="stylesheet" href="volunteer.html">
    <link rel="stylesheet" href="onlinegiving.html">
    <link rel="stylesheet" href="mission.html">
    <link rel="stylesheet" href="about.html">

</head>
<body>
    <div id="navbar"></div>
    <header>
        <img src="images/faith.jpg" width="200" height="100" alt="faith" class="faith">
        <div id="navbar"></div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="mission.html">Mission</a></li>
                <li><a href="onlinegiving.html">Online Giving</a></li>
                <li><a href="volunteer.html">Volunteer</a></li>
                <li><a href="sermon.html">Sermons</a></li>
                <li><a href="servicetime.html">Service Times</a></li>
                <li><a href="ministries.html">Ministries</a></li>
                <li><a href="churchhistory.html">Church History</a></li>
                <li><a href="contact.html">Contact Us</a></li>
               
            </ul>
        </nav>
    </header>
    <footer>
        <p>&copy; 2024 Refresh of Jesus Christ Prayer House Ministries</p>
    </footer>

    <script src="scripts.js"></script>
    <script src="navbar.js"></script>
    <script>
        fetch('navbar.html')
            .then(response => response.text())
            .then(data => {
                document.getElementById('navbar').innerHTML = data;
            });
    </script>
</body>
</html>
