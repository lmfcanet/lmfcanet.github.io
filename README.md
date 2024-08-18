<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Audio Examples for GTCRN</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 90%;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .audio-group {
            margin-bottom: 20px;
        }
        .audio-label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }
        button {
            background-color: #ff4136;
            color: white;
            border: none;
            padding: 10px 20px;
            text-transform: uppercase;
            border-radius: 5px;
            cursor: pointer;
            margin: 10px 0;
        }
        button:hover {
            background-color: #e22e12;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Audio Examples for GTCRN</h1>
        <div class="buttons">
            <button onclick="window.location.href='code_url'">Code</button>
            <button onclick="window.location.href='paper_url'">Paper</button>
        </div>
        <div class="audio-group">
            <span class="audio-label">Noisy</span>
            <!-- Add multiple audio elements as needed -->
            <audio controls>
                <source src="path_to_noisy_audio1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
        <div class="audio-group">
            <span class="audio-label">Enhanced by RNNNoise</span>
            <audio controls>
                <source src="path_to_rnnnoise_audio1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
        <div class="audio-group">
            <span class="audio-label">Enhanced by GTCRN</span>
            <audio controls>
                <source src="path_to_gtcrn_audio1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
        <div class="audio-group">
            <span class="audio-label">Clean</span>
            <audio controls>
                <source src="path_to_clean_audio1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
    </div>
</body>
</html>

