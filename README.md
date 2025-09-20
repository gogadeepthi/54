<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style> .out{color: purple; font-weight: bold;}</style>
    
</head>
<body>
    <h1> Event via EventListener </h1>
    <button id="btn">Click Me </button>
    <p id="msg" class="out"></p>
    <script>
        document.getElementById("btn").addEventListener("click", function() {
            document.getElementById("msg").innerText="Handled by addEventListener";
        });
    </script>
</body>
</html>
