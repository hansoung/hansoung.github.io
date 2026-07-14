<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Strength Analyzer</title>
    <style>
        body { font-family: sans-serif; margin: 40px; }
        .container { max-width: 600px; }
        .input-group { margin-bottom: 20px; }
        input { padding: 8px; width: 70%; font-size: 16px; }
        button { padding: 8px 15px; font-size: 16px; cursor: pointer; }
        .dashboard { display: flex; gap: 20px; margin-top: 20px; }
        .column { flex: 1; padding: 10px; border-radius: 4px; min-height: 150px; }
        .strong-bg { background-color: #e6f4ea; border: 1px solid #137333; }
        .medium-bg { background-color: #fef7e0; border: 1px solid #b06000; }
        .weak-bg { background-color: #fce8e6; border: 1px solid #c5221f; }
        h3 { margin-top: 0; }
        ul { list-style-type: none; padding: 0; }
        li { padding: 5px 0; border-bottom: 1px solid #ddd; word-break: break-all; }
    </style>
</head>
<body>

<div class="container">
    <h2>Password Strength Evaluator</h2>
    <div class="input-group">
        <input type="text" id="passwordInput" placeholder="Enter a password to test...">
        <button onclick="evaluatePassword()">Analyze</button>
    </div>

    <div class="dashboard">
        <div class="column strong-bg">
            <h3>Strong (Good)</h3>
            <ul id="strongList"></ul>
        </div>
        <div class="column medium-bg">
            <h3>Medium</h3>
            <ul id="mediumList"></ul>
        </div>
        <div class="column weak-bg">
            <h3>Weak (Bad)</h3>
            <ul id="weakList"></ul>
        </div>
    </div>
</div>

<script src="app.js"></script>
</body>
</html>
