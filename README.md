<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Result Portal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to the Student Result Portal</h1>

        <label for="rollNumber">Enter Roll Number:</label>
        <input type="text" id="rollNumber" placeholder="Enter Roll Number">
        <button onclick="checkResult()">Check Result</button>

        <div id="result" class="result">
            <h2>Result: <span id="resultMessage"></span></h2>
        </div>

        <div id="errorMessage" class="error"></div>

        <h3>Admin Panel (For Adding Results)</h3>
        <div class="admin-panel">
            <label for="adminRollNumber">Roll Number:</label>
            <input type="text" id="adminRollNumber" placeholder="Enter Roll Number">
            <label for="adminResult">Result (Pass/Fail):</label>
            <input type="text" id="adminResult" placeholder="Enter Result">
            <button onclick="addResult()">Add Result</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
