# sample2-
dind't understood the first time how to use the git 
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Intermediate HTML Example</title>
    <style>
        /* CSS styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to the Intermediate HTML Example</h1>
        
        <p>This is a simple HTML document with some intermediate-level features.</p>
        
        <form id="myForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            
            <button type="button" onclick="submitForm()">Submit</button>
        </form>
        
        <p id="message"></p>
    </div>

    <script>
        // JavaScript function
        function submitForm() {
            const name = document.getElementById("name").value;
            const email = document.getElementById("email").value;
            
            const message = `Hello, ${name}! Your email (${email}) has been submitted.`;
            document.getElementById("message").textContent = message;
        }
    </script>
</body>
</html>
