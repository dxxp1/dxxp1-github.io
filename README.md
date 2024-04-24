 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buzzer with Timer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="timer">00:00</div>
    <div class="host-controls">
        <label for="minutes">Minutes:</label>
        <input type="number" id="minutes" min="0">
        <label for="seconds">Seconds:</label>
        <input type="number" id="seconds" min="0" max="59">
        <button id="setTime">Set Time</button>
    </div>
    <div class="participant-controls">
        <label for="roomCode">Room Code:</label>
        <input type="text" id="roomCode" placeholder="Enter room code">
        <label for="participantName">Your Name:</label>
        <input type="text" id="participantName" placeholder="Your Name">
        <button id="join">Join Room</button>
    </div>
    <div class="buzzer">
        <button id="buzz">Buzz!</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
