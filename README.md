# myrepo
<br>
harshit here
<br>
doing coding stuff
<br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOST - Your Friendly Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3498db; /* Blue */
            padding: 10px;
            text-align: center;
            color: white;
        }

        section {
            padding: 20px;
            background-color: #5dade2; /* Light Blue */
            color: white;
        }

        section:nth-child(2) {
            background-color: #2980b9; /* Darker Blue */
        }

        section:nth-child(3) {
            background-color: #1f618d; /* Even Darker Blue */
        }

        section:nth-child(4) {
            background-color: #154360; /* Deep Blue */
        }

        section:nth-child(5) {
            background-color: #0e2a47; /* Darkest Blue */
        }

        footer {
            background-color: #3498db;
            padding: 10px;
            text-align: center;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        form {
            max-width: 400px;
            margin: 20px auto;
            background-color: #3498db;
            padding: 20px;
            color: white;
            border-radius: 5px;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }

        button {
            background-color: #154360; /* Deep Blue */
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>DOST - Your Friendly Website</h1>
    </header>

    <section>
        <h2>Section 1</h2>
        <p>This is the first section of the website.</p>
    </section>

    <section>
        <h2>Section 2</h2>
        <p>This is the second section of the website.</p>
    </section>

    <section>
        <h2>Section 3</h2>
        <p>This is the third section of the website.</p>
    </section>

    <section>
        <h2>Section 4</h2>
        <p>This is the fourth section of the website.</p>
    </section>

    <section>
        <h2>Section 5</h2>
        <p>This is the fifth section of the website.</p>
    </section>

    <footer>
        <p>&copy; 2023 DOST - Your Friendly Website</p>
    </footer>

    <form>
        <h2>Login</h2>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="age">Age:</label>
        <input type="number" id="age" name="age" required>

        <label for="purpose">Purpose:</label>
        <input type="text" id="purpose" name="purpose" required>

        <label for="type">Type:</label>
        <input type="text" id="type" name="type" required>

        <button type="submit">Login</button>
    </form>

</body>
</html>
