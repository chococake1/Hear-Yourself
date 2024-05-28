---
title: Testing
published_at: 2024-05-28
snippet: IDP
disable_html_sanitization: true
---
<!DOCTYPE html>
<html lang="en">


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Symphony</title>
    <link rel="stylesheet" href="styles/styles.css">

</head>
<body>
    <script src="script.js"></script>
    <div class="container">
        <h1>Create Your Symphony</h1>
        <div id="questions">
            <div class="question">
                <p>1. Test Q1:</p>
                <button class="answer" data-sound="sound1.mp3">Happy</button>
                <button class="answer" data-sound="sound2.mp3">Sad</button>
                <button class="answer" data-sound="sound3.mp3">Excited</button>
            </div>
            <div class="question">
                <p>2. Choose a tempo:</p>
                <button class="answer" data-sound="sound4.mp3">Fast</button>
                <button class="answer" data-sound="sound5.mp3">Moderate</button>
                <button class="answer" data-sound="sound6.mp3">Slow</button>
            </div>
            <div class="question">
                <p>3. Choose an instrument:</p>
                <button class="answer" data-sound="sound7.mp3">Piano</button>
                <button class="answer" data-sound="sound8.mp3">Guitar</button>
                <button class="answer" data-sound="sound9.mp3">Violin</button>
            </div>
        </div>
        <div id="controls">
            <button id="playSymphony">Play Symphony</button>
            <button id="stopSymphony">Stop Symphony</button>
        </div>
    </div>
</body>
</html>
