<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Music Recommendation System</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #0f172a;
            color: #e5e7eb;
        }

        header {
            background: #020617;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            color: #38bdf8;
        }

        section {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: #22d3ee;
        }

        ul {
            line-height: 1.8;
        }

        .box {
            background: #020617;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 30px;
        }

        iframe {
            width: 100%;
            height: 700px;
            border: none;
            border-radius: 10px;
            background: #000;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #020617;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>🎵 Music Recommendation System Using Facial Expressions</h1>
    <p>Computer Vision • Deep Learning • Streamlit</p>
</header>

<section>
    <div class="box">
        <h2>📌 Overview</h2>
        <p>
            This project is a real-time music recommendation system that detects a user's
            facial expression using a webcam, classifies the emotion using a CNN model,
            and recommends music accordingly.
        </p>
        <p>
            It combines Computer Vision, Deep Learning, and Data Processing to deliver
            a personalized user experience.
        </p>
    </div>

    <div class="box">
        <h2>🚀 Features</h2>
        <ul>
            <li>Real-time face detection using OpenCV</li>
            <li>Emotion recognition using a pre-trained CNN model</li>
            <li>Music recommendation based on detected emotion</li>
            <li>Interactive web interface using Streamlit</li>
            <li>Lightweight and easy to run locally</li>
        </ul>
    </div>

    <div class="box">
        <h2>🧠 Technologies Used</h2>
        <ul>
            <li>Python</li>
            <li>Streamlit (Web Interface)</li>
            <li>OpenCV (Face Detection)</li>
            <li>TensorFlow / Keras (CNN Model)</li>
            <li>NumPy & Pandas (Data Handling)</li>
        </ul>
    </div>

    <div class="box">
        <h2>🖥️ Live Application</h2>
        <p>
            Make sure the Streamlit app is running using:
            <br><br>
            <code>streamlit run app.py</code>
        </p>
        <p>
            Once running, the app will be embedded below:
        </p>

        <!-- Streamlit App Embed -->
        <iframe src="http://localhost:8501"></iframe>
    </div>
</section>

<footer>
    <p>Developed by Anushka Consul | Music Recommendation System</p>
</footer>

</body>
</html>
