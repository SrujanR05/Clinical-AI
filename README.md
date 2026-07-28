<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Clinical Text Analysis System</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#0f172a;
            color:white;
        }

        header{
            background:#111827;
            padding:20px;
            text-align:center;
            border-bottom:3px solid #3b82f6;
        }

        header h1{
            color:#3b82f6;
            margin-bottom:10px;
        }

        header p{
            color:#cbd5e1;
        }

        .hero{
            max-width:1000px;
            margin:auto;
            padding:60px 20px;
            text-align:center;
        }

        .hero h2{
            font-size:40px;
            margin-bottom:20px;
        }

        .hero p{
            color:#d1d5db;
            font-size:18px;
            line-height:1.8;
        }

        .btn{
            display:inline-block;
            margin-top:30px;
            padding:14px 28px;
            background:#2563eb;
            color:white;
            text-decoration:none;
            border-radius:8px;
            transition:.3s;
        }

        .btn:hover{
            background:#1d4ed8;
        }

        .section{
            max-width:1100px;
            margin:auto;
            padding:40px 20px;
        }

        .section h2{
            text-align:center;
            color:#60a5fa;
            margin-bottom:30px;
        }

        .cards{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:20px;
        }

        .card{
            background:#1e293b;
            padding:20px;
            border-radius:10px;
            transition:.3s;
        }

        .card:hover{
            transform:translateY(-8px);
            box-shadow:0 10px 20px rgba(0,0,0,.4);
        }

        .card h3{
            color:#38bdf8;
            margin-bottom:15px;
        }

        .tech{
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
            gap:15px;
            margin-top:20px;
        }

        .tech span{
            background:#2563eb;
            padding:10px 18px;
            border-radius:20px;
        }

        footer{
            text-align:center;
            padding:20px;
            background:#111827;
            margin-top:50px;
            color:#cbd5e1;
        }
    </style>
</head>

<body>

<header>
    <h1>🏥 AI Clinical Text Analysis System</h1>
    <p>AI Powered Healthcare Risk Prediction & Clinical Text Analysis</p>
</header>

<section class="hero">
    <h2>Transform Clinical Notes into Actionable Insights</h2>

    <p>
        AI Clinical Text Analysis System is a modern healthcare web application
        that analyzes unstructured clinical notes using Artificial Intelligence.
        It predicts patient risk levels, extracts symptoms, processes medical
        documents through OCR, and provides intelligent healthcare insights.
    </p>

    <a href="https://github.com/SrujanR05/Clinical-AI-main" class="btn">
        View GitHub Repository
    </a>
</section>

<section class="section">

    <h2>✨ Key Features</h2>

    <div class="cards">

        <div class="card">
            <h3>🧠 AI Risk Prediction</h3>
            <p>Predict High, Medium and Low health risk using Machine Learning.</p>
        </div>

        <div class="card">
            <h3>📋 Symptom Extraction</h3>
            <p>Automatically extracts symptoms from unstructured clinical text.</p>
        </div>

        <div class="card">
            <h3>📄 OCR Support</h3>
            <p>Upload PDFs or medical reports and extract text using OCR.</p>
        </div>

        <div class="card">
            <h3>📊 Dashboard</h3>
            <p>Interactive dashboard showing analysis history and patient insights.</p>
        </div>

    </div>

</section>

<section class="section">

    <h2>🛠 Technologies Used</h2>

    <div class="tech">
        <span>React</span>
        <span>Python Flask</span>
        <span>Firebase</span>
        <span>Machine Learning</span>
        <span>BERT</span>
        <span>Scikit-Learn</span>
        <span>OCR</span>
        <span>Chart.js</span>
    </div>

</section>

<footer>
    <p>
        © 2026 AI Clinical Text Analysis System |
        Built using React, Flask, Firebase & Artificial Intelligence.
    </p>
</footer>

</body>
</html>
