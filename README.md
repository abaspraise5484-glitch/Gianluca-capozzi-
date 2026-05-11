# Gianluca-capozzi-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Online Quiz Entry</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f0f0f;
    color: white;
    text-align: center;
}

.container {
    max-width: 600px;
    margin: auto;
    padding: 20px;
}

.card {
    background: #1e1e1e;
    padding: 18px;
    margin-top: 15px;
    border-radius: 10px;
}

h1 {
    color: gold;
}

input {
    width: 90%;
    padding: 12px;
    margin-top: 10px;
    border-radius: 6px;
    border: none;
}

button {
    width: 95%;
    padding: 14px;
    margin-top: 10px;
    background: gold;
    border: none;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background: #ffd700;
}

.small {
    font-size: 12px;
    color: #aaa;
}
</style>

</head>

<body>

<div class="container">

<h1>🧠 Online Quiz Entry</h1>

<div class="card">
<p>This is a simple knowledge quiz and entry form.</p>
<p>All participants are added to a random selection pool for future promotions.</p>
</div>

<form>

<div class="card">
<h3>Question 1</h3>
<p>Who is the governor of your state?</p>
<input type="text" name="answer" required>
</div>

<div class="card">
<h3>Participant Details</h3>

<input type="text" placeholder="Full Name" required>
<input type="text" placeholder="Phone Number" required>
<input type="email" placeholder="Email Address" required>
<input type="text" placeholder="State" required>
</div>

<div class="card">
<button type="submit">SUBMIT ENTRY</button>
</div>

</form>

<div class="card small">
Note: This is a free entry quiz. No purchase or payment is required.  
Participants may be contacted for future promotional campaigns.
</div>

</div>

</body>
</html>
