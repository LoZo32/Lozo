<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Day Playful Expression</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            background-color: #ffc0cb;
            margin-top: 50px;
        }

        h1 {
            color: #ff1493;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 20px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #ff69b4;
            color: #fff;
        }
    </style>
</head>
<body>
    <h1>Will you be my Valentine?</h1>
    <button onclick="acceptProposal()">Yes</button>
    <button onclick="rejectProposal()">No</button>

    <script>
        function acceptProposal() {
            alert("Yay! You've made my day! 🥰");
        }

        function rejectProposal() {
            alert("Sorry, 'No' is not an option today. 😉 Try again with a 'Yes'!");
        }
    </script>
</body>
</html>
