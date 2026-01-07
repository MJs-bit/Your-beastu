<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unlock the Surprise</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #ffe6f2, #ffb3d9);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #333;
        }
        .lock-container {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            text-align: center;
            max-width: 400px;
        }
        input {
            padding: 10px;
            font-size: 18px;
            border: 2px solid #ff69b4;
            border-radius: 5px;
            width: 80%;
            margin: 10px 0;
        }
        button {
            background: #ff69b4;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background: #ff1493;
        }
        .error {
            color: red;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="lock-container">
        <h1>🔒 Enter Her Birth Date to Unlock</h1>
        <p>Hint: It's a special day! (Format: DD-MMMM, e.g., 21-July)</p>
        <input type="text" id="birthdate" placeholder="e.g., 21-July">
        <button onclick="checkDate()">Unlock</button>
        <p id="error" class="error"></p>
    </div>
    <script>
        function checkDate() {
            const input = document.getElementById('birthdate').value.trim().toLowerCase();
            const correct = '21-july';
            if (input === correct || input === '21 july') {
                window.location.href = 'card2.html';
            } else {
                document.getElementById('error').textContent = 'Oops! Try again. 😊';
            }
        }
    </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Mahila Mitrra Day</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #ffe6f2, #ffb3d9);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            text-align: center;
            max-width: 500px;
            position: relative;
        }
        .card h1 {
            color: #ff69b4;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .emojis {
            font-size: 3em;
            margin: 20px 0;
        }
        button {
            background: #ff69b4;
            color: white;
            border: none;
            padding: 12px 25px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background: #ff1493;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Happy Mahila Mitrra Day!</h1>
        <div class="emojis">😊👻🎉</div>
        <p>A special wish for an amazing friend! 💖</p>
        <button onclick="window.location.href='card3.html'">Next Surprise</button>
    </div>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Heartfelt Message</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #ffe6f2, #ffb3d9);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            text-align: center;
            max-width: 600px;
            line-height: 1.6;
            font-size: 18px;
            color: #333;
        }
        .card h1 {
            color: #ff69b4;
            font-size: 2em;
            margin-bottom: 20px;
        }
        .message {
            text-align: left;
            margin: 20px 0;
            font-style: italic;
        }
        .highlight {
            font-size: 1.2em;
            font-weight: bold;
            color: #ff1493;
        }
        .emojis {
            font-size: 2em;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>A Lovely Card for You</h1>
        <div class="emojis">🥰 🙏</div>
        <div class="message">
            <p class="highlight">Sabse pehle to me apse maafi mangta hu.. Sorry my sweetuuu</p>
            <p>Jabse apse mila hu tabse meri zindagi me khushiya aa gayi hai. Ap meri zindagi ka wo hissa ho jise me kar ke bhi na bhulu. Me is janam me to kya har janam me apka friend banana chaahunga. Apke sath bitaye hue wo lamhe... Us din hamara ek sath naachna aur gaana, uske baad kuch yaado ke liye li hui wo tasvire jinhe me aj bhi dekhta hu to chehre pe ek muskurahat si aa jaati hai. Un lamho ko agar firse jeene ka mauka mila to me firse jeena chaahunga. Us din hamne jo koi bhi galtiya ki thi wo me firse karna chaahunga—apka mere haatho me nail polish lagana aur fir mujhe kuch ho jaane par apka wo kass ke gale se lagana. Wo din bhi kya din tha... Agar zindagi me ap jese dost mujhe pehle hi mil gaye hote to aj me kuch aur hi hota. Jo mere chehre ki khushi kisi wajah se chali gayi thi wo shayad na jaati agar ap mujhe pehle hi mil gaye hote. Bus itna hi kehna chaahunga apse me: Thank you soooo much 🥰💓💞 har cheez ke liye....</p>
            <p>Orr sorry meri saari ki hui galtiyo ke liye... 🥺</p>
        </div>
        <p>With all my love and gratitude! 💖</p>
    </div>
</body>
</html>
