<!doctype html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Nard Smits</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<div class="container">
    <header>
    <div class="header_background">
    <div id="logo"><a href="#"><img src="logo.png"></a></div>
    <ul class="nav_menu">
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">Over mij</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
    <div class="clear"></div>
    </div>
    </header>

    <section id="mainBody">
        <div id="welcomeDiv"><div id="headerFont">Welkom op mijn site</div>
            Mijn naam is Nard Smits, ik ben 17 jaar oud en woon in Den Bosch.
        </div>
        <div id="newsLetter">
            <form action="action_page.php" method="POST">
                <div id="smallPadding">Naam</div>
                <input type="text" name="Name">
                <br>
                <div id="smallPadding">Email</div>
                <input type="email" name="Email">
                <br>
                <input type="submit" name="Submit">
            </form>
        </div>

        <div class="clear"></div>

        <div id="leftDiv">
          <div id="img1"></div>
        </div>
        <div id="rightDiv">
          <div id="img2"></div>
        </div>
    </section>
    <div class="clear"></div>

    <footer>Nard Smits &#169; 2015</footer>
</div>
</body>
</html>

