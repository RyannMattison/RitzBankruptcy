<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ritz Bankruptcy Notice</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        h1 {
            color: red;
        }
        .countdown {
            font-size: 24px;
            font-weight: bold;
            color: darkred;
        }
        .footer {
            font-size: 12px;
            color: gray;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Company Logo -->
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Ritz-Cracker.png/600px-Ritz-Cracker.png" width="200" alt="Ritz Logo">
        
        <!-- Official Header -->
        <h1>Official Bankruptcy Notice</h1>
        <p><strong>Ritz Holdings, LLC</strong><br>
        1234 Snack Lane, Suite 500, New York, NY 10001<br>
        <strong>Case No: 2025-BK-0421</strong></p>

        <!-- Breaking News Section -->
        <h3>BREAKING NEWS: Ritz Crackers Files for Bankruptcy</h3>
        <p>New York (April 1, 2025) – In a shocking turn of events, Ritz Holdings, LLC has filed for Chapter 11 bankruptcy protection, citing unexpected losses in the snack industry. Analysts suggest that increased competition and declining consumer interest in traditional crackers have led to this decision.</p>

        <!-- Countdown Timer -->
        <p><strong>Time Remaining Until Liquidation:</strong></p>
        <p class="countdown" id="countdown"></p>

        <!-- Fake Creditor Claim Form -->
        <h3>Creditor Claim Form</h3>
        <form>
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name"><br><br>
            
            <label for="amount">Claim Amount ($):</label><br>
            <input type="number" id="amount" name="amount"><br><br>

            <label for="reason">Reason for Claim:</label><br>
            <textarea id="reason" name="reason"></textarea><br><br>

            <input type="submit" value="Submit Claim">
        </form>

        <!-- Downloadable PDF Link -->
        <p><a href="bankruptcy-filing.pdf" download>Download Official Bankruptcy Notice (PDF)</a></p>

        <!-- Legal Disclaimer -->
        <p class="footer">This is an official announcement from Ritz Holdings, LLC. All creditor claims must be filed before May 1, 2025.</p>
    </div>

    <!-- Countdown Timer Script -->
    <script>
        function countdown() {
            const liquidationDate = new Date("May 1, 2025").getTime();
            const now = new Date().getTime();
            const timeLeft = liquidationDate - now;

            const days = Math.floor(timeLeft / (1000 * 60 * 60 * 24));
            document.getElementById("countdown").innerHTML = days + " days remaining";
        }
        setInterval(countdown, 1000);
    </script>

    <!-- Fake Restricted Access Pop-up -->
    <script>
        alert("⚠️ Restricted Access: This page is for authorized creditors only.");
    </script>

</body>
</html>



