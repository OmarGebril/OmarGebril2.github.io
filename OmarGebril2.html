<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rock Paper Scissors</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: black; /* Set background color to black */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: white; /* Set text color to white */
        }

        .container {
            text-align: center;
        }

        h1 {
            color: white; /* Set text color to white */
            margin-bottom: 20px;
        }

        .options {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .options button {
            margin: 0 10px;
            padding: 20px 30px;
            font-size: 32px;
            cursor: pointer;
            background-color: #007bff; /* blue color */
            color: white;
            border: none;
            border-radius: 50%; /* rounded buttons */
            transition: background-color 0.3s;
        }

        .options button:hover {
            background-color: #0056b3; /* darker blue on hover */
        }

        #result {
            font-size: 24px;
            font-weight: bold;
            color: white; /* Set text color to white */
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Rock Paper Scissors</h1>
        <p>This is a best of 5 rounds game. Click on one of the symbols below to start playing:</p>
        <div class="options">
            <button onclick="play('rock')">✊</button>
            <button onclick="play('paper')">✋</button>
            <button onclick="play('scissors')">✌️</button>
        </div>
        <div id="result">Round 0: You chose -, computer chose -. Start the game!</div>
        <div id="score">Score: You 0 - Computer 0</div>
    </div>

    <script>
        let userScore = 0;
        let computerScore = 0;
        let round = 0;

        function play(userChoice) {
            const choices = ['rock', 'paper', 'scissors'];
            const computerChoice = choices[Math.floor(Math.random() * 3)];

            let result;

            if (userChoice === computerChoice) {
                result = 'It\'s a tie!';
            } else if (
                (userChoice === 'rock' && computerChoice === 'scissors') ||
                (userChoice === 'paper' && computerChoice === 'rock') ||
                (userChoice === 'scissors' && computerChoice === 'paper')
            ) {
                result = 'You win!';
                userScore++;
            } else {
                result = 'Computer wins!';
                computerScore++;
            }

            round++;

            document.getElementById('result').innerText = `Round ${round}: You chose ${userChoice}, computer chose ${computerChoice}. ${result}`;
            document.getElementById('score').innerText = `Score: You ${userScore} - Computer ${computerScore}`;

            if (userScore === 3 || computerScore === 3) {
                if (userScore === 3) {
                    document.getElementById('result').innerText += '\nCongratulations! You win the game!';
                } else {
                    document.getElementById('result').innerText += '\nSorry, you lost the game!';
                }

                // Disable buttons after best of 5 rounds
                document.querySelectorAll('.options button').forEach(button => button.disabled = true);
            }
        }
    </script>
</body>
</html>
