<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>One Important Question 💖</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }
        .box {
            background: rgba(0,0,0,0.2);
            padding: 40px;
            border-radius: 12px;
        }
        button {
            padding: 12px 25px;
            font-size: 16px;
            margin: 10px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
        }
        .yes {
            background-color: #4CAF50;
            color: white;
        }
        .no {
            background-color: #f44336;
            color: white;
        }
    </style>
</head>
<body>

<div class="box">
    <h1 id="question">Can I ask you one important question? 💙</h1>
    <div id="buttons">
        <button class="yes" onclick="nextQuestion()">Yes</button>
        <button class="no" onclick="alert('Please say yes 😊')">No</button>
    </div>
</div>

<script>
    function nextQuestion() {
        document.getElementById("question").innerHTML = "Will you marry me? 💍❤️";
        document.getElementById("buttons").innerHTML =
            '<button class="yes" onclick="alert(`She said YES 💖💍`)">Yes</button>' +
            '<button class="no" onclick="alert(`Think again 😄`)">No</button>';
    }
</script>

</body>
</html>
