<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
   <title>Tatiana Antonia Morés - Profile</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f4f8;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 2.5em;
            color: #333;
        }

        .subtitle {
            font-size: 1.2em;
            color: #666;
        }

        .bio {
            margin: 20px 0;
        }

        h2 {
            font-size: 1.5em;
            color: #007BFF;
        }

        p {
            line-height: 1.6;
            color: #444;
        }

        footer {
            text-align: center;
            margin-top: 30px;
        }

        footer a {
            color: #007BFF;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Tatiana Antonia Morés</h1>
            <p class="subtitle">Oral and Maxillofacial Surgeon</p>
        </header>
        <section class="bio">
            <h2>About Me</h2>
            <p>
                I am 29 years old and a specialist in Surgery and Traumatology. Currently, I am seeking opportunities 
                and learning in the field of web development (front-end developer). Living in Brazil, but open to the 
                world and possibilities.
            </p>
            <h2>What Inspired My Career Change?</h2>
            <p>
                The job market, the daily routine, the chance to have different experiences, 
                the contact with technology and development, the opportunity to create and change the world with technology, 
                and the desire to step out of stagnation and my comfort zone.
            </p>
        </section>
        <footer>
            <p>Connect with me on <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank">GitHub</a></p>
        </footer>
    </div>
  <script>
  function displayProfile() {
    const name = "Tatiana Antonia Morés";
    const age = 29;
    const profession = "Oral and Maxillofacial Surgeon";
    const specialization = "specialist in Surgery and Traumatology";
    const goal = "currently seeking opportunities and learning in the field of web development (front-end developer)";
    const location = "living in Brazil, but open to the world and possibilities";
    
    const reasonForChange = "What led me to change the course of my professional career? " +
        "I would say the job market, the daily routine, the possibility of having different experiences, " +
        "the contact with technology and development, the chance to create and change the world with technology, " +
        "as well as the desire to step out of stagnation and the comfort zone.";
    
    // Constructing the profile message
    const profileMessage = `Hello! My name is ${name}, I am ${age} years old, I am an ${profession} ${specialization}, ` +
        `${goal}. I am ${location}. \n\n${reasonForChange}`;

    // Display the profile message in an alert
    alert(profileMessage);
}

// Ask the user if they want to see the profile
const userResponse = prompt("Would you like to learn more about my profile? (yes/no)").toLowerCase();

if (userResponse === 'yes') {
    displayProfile();
} else {
    alert("Thank you! Have a great day!");
}
</script>
</body>
</html>
