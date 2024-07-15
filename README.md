<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome</title>
    <link rel="icon" type="image/png" href="acm2.png">
    <link rel="stylesheet" href="styles.css">
</head>
<body style="background-color: #f4f6f8;">

    <!-- Top Frame -->
    <header>
        <div class="image-container">
            <img src="acm.png" style="width: 340px;" alt="Association for Computing Machinery">
        </div>
    </header>

    <!-- Main Frame -->
    <frameset rows="20%,*">
        <frameset cols="100%">
            <frame src="topframe.html" name="topf">
        </frameset>
        <frameset cols="15%, *">
            <frame src="leftframe.html" name="leftf">
            <frame src="rightframe.html" name="rightf">
        </frameset>
    </frameset>

    <!-- About Page -->
    <div style="background-color: rgb(240, 234, 234); border-radius: 7px; margin: 20px; padding: 10px;">
        <h2><i>About us:</i></h2>
        <div style="background-color: rgb(240, 234, 234);border-radius: 7px;">
            <h3><i>Overview</i></h3>
            <p>ACM is organized into over 180 local professional chapters[11] and 38 Special Interest Groups (SIGs),[12] through which it conducts most of its activities. Additionally, there are over 680 student chapters.[11] The first student chapter was founded in 1961 at the University of Louisiana at Lafayette.[13][14]  Many of the SIGs, such as SIGGRAPH, SIGDA, SIGPLAN, SIGCSE and SIGCOMM, sponsor regular conferences, which have become famous as the dominant venue for presenting innovations in certain fields. The groups also publish a large number of specialized journals, magazines, and newsletters.[15] ACM also sponsors other computer science related events such as the worldwide ACM International Collegiate Programming Contest (ICPC), and has sponsored some other events such as the chess match between Garry Kasparov and the IBM Deep Blue computer.[16].</p>
            <br>
            <h3><i>Association for Computing Machinery at a Glance</i></h3>
            <p>In 1997, ACM Press published Wizards and Their Wonders: Portraits in Computing (ISBN 0897919602), written by Christopher Morgan, with new photographs by Louis Fabian Bachrach. The book is a collection of historic and current portrait photographs of figures from the computer industry.</p>
        </div>
    </div>

    <!-- Contact Us Page -->
    <div style="background-color: #fefeff; border-radius: 7px; margin: 20px; padding: 10px;">
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/mwpepnyz" method="POST">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="_replyto"><br>
            <label for="review">Review:</label><br>
            <textarea id="review" name="review" rows="4" cols="50"></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </div>

    <!-- Events Page -->
    <div style="background-color: #f3f5f6; border-radius: 7px; margin: 20px; padding: 10px;">
        <h2>Events Organized by ACM Student Chapter, Anurag University</h2>
        <ul>
            <li>
                <strong>Pre-Conference Workshop on Cloud Services</strong><br>
                Date: December 15-16, 2023<br>
                Time: 9 am to 4 pm<br>
                Venue: E 703, Anurag University<br>
                Objective: Increase awareness about cloud technologies among students.<br>
                Summary: The workshop included sessions on cloud fundamentals, hands-on virtual machine practice, and practical applications across various platforms.
            </li>
            <li>
                <strong>Digital Literacy Day at ZPHS, Korremula</strong><br>
                Date: December 11, 2023<br>
                Time: 12:30 PM – 2:00 PM<br>
                Venue: ZPHS Korremula<br>
                Objective: Instill digital literacy skills among rural students.<br>
                Summary: Focused on introducing Microsoft applications and promoting interactive learning methods to enhance digital understanding.
            </li>
            <li>
                <strong>Digital Awareness Campaign in Collaboration with NSS</strong><br>
                Date: December 11, 2023<br>
                Time: 12:30 Noon – 2:00 PM<br>
                Venue: ZPHS Korremula<br>
                Objective: Impart technological awareness to young minds.<br>
                Summary: A joint effort by NSS and ACM Student Chapter to educate students on digital landscapes, emphasizing computer usage and applications.
            </li>
        </ul>
    </div>

</body>
</html>
