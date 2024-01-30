
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moderate Web Application</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        form {
            display: flex;
            flex-direction: column;
            max-width: 300px;
            margin: 0 auto;
        }
        input, button {
            margin: 10px 0;
            padding: 10px;
        }
    </style>
</head>
<body>

    <h1>Welcome to the Moderate Web Application!</h1>

    <form onsubmit="submitForm(event)">
        <label for="name">Your Name:</label>
        <input type="text" id="name" required>

        <label for="age">Your Age:</label>
        <input type="number" id="age" required>

        <button type="submit">Submit</button>
    </form>

    <div id="result"></div>

    <script>
        function submitForm(event) {
            event.preventDefault();
            
            var name = document.getElementById('name').value;
            var age = document.getElementById('age').value;

            var greeting = `Hello, ${name}!`;
            var ageInfo = `You are ${age} years old.`;

            document.getElementById('result').innerHTML = `<p>${greeting} ${ageInfo}</p>`;
        }
    </script>

</body>
</html>
