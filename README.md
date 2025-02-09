<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Question</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
        }
        .container {
            display: inline-block;
            padding: 20px;
            border: 2px solid #000;
            border-radius: 10px;
            background-color: #ffe6e6;
        }
        .buttons {
            margin-top: 20px;
        }
        #noButton {
            position: relative;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Will you be my Valentine?</h2>
        <div class="buttons">
            <button id="yesButton">Yes</button>
            <button id="noButton">No</button>
        </div>
    </div>

    <script>
        document.getElementById("yesButton").addEventListener("click", function() {
            alert("Yay! ❤️ See you on Valentine's Day!");
            window.location.href = "yes_page.html"; // Redirect to a yes page
        });

        document.getElementById("noButton").addEventListener("mouseover", function() {
            let noButton = document.getElementById("noButton");
            let randomX = Math.random() * (window.innerWidth - 100);
            let randomY = Math.random() * (window.innerHeight - 50);
            noButton.style.position = "absolute";
            noButton.style.left = randomX + "px";
            noButton.style.top = randomY + "px";
        });
    </script>

</body>
</html>
        <h2>Will you be my Valentine?</h2>
        <div class="buttons">
            <button id="yesButton">Yes</button>
            <button id="noButton">No</button>
        </div>
    </div>

    <script>
        document.getElementById("yesButton").addEventListener("click", function() {
            alert("Yay! ❤️ See you on Valentine's Day!");
            window.location.href = "yes_page.html"; // Redirect to a yes page
        });

        document.getElementById("noButton").addEventListener("mouseover", function() {
            let noButton = document.getElementById("noButton");
            let randomX = Math.random() * (window.innerWidth - 100);
            let randomY = Math.random() * (window.innerHeight - 50);
            noButton.style.position = "absolute";
            noButton.style.left = randomX + "px";
            noButton.style.top = randomY + "px";
        });
    </script>

</body>
</html>
