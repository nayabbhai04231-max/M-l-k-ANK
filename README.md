# M-l-k-ANK
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Investment Dashboard</title>

<style>
body {
  margin: 0;
  font-family: Arial;
  background: #f5f5f5;
}

/* Header */
.header {
  background: #1e5aa8;
  color: white;
  padding: 15px;
  border-radius: 0 0 20px 20px;
}

.header h2 {
  margin: 0;
}

/* Balance Card */
.balance {
  background: #4CAF50;
  margin: 15px;
  padding: 20px;
  border-radius: 15px;
  color: white;
  text-align: center;
}

/* Buttons */
.actions {
  display: flex;
  justify-content: space-around;
  margin: 10px;
}

button {
  padding: 10px 20px;
  border: none;
  border-radius: 10px;
  background: #1e5aa8;
  color: white;
  cursor: pointer;
}

/* Cards */
.card {
  background: white;
  margin: 15px;
  padding: 15px;
  border-radius: 15px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.buy-btn {
  float: right;
  background: green;
}
</style>

</head>

<body>

<div class="header">
  <h2>Hi, User 👋</h2>
  <p>ID: 123456</p>
</div>

<div class="balance">
  <h1>₹100</h1>
  <p>Total Balance</p>
</div>

<div class="actions">
  <button onclick="deposit()">Deposit</button>
  <button onclick="withdraw()">Withdraw</button>
</div>

<div class="card">
  <h3>Share Earn 1</h3>
  <p>Price: ₹495</p>
  <p>Profit: ₹8910</p>
  <button class="buy-btn" onclick="buy()">Buy</button>
</div>

<div class="card">
  <h3>Share Earn 2</h3>
  <p>Price: ₹1395</p>
  <p>Profit: ₹25110</p>
  <button class="buy-btn" onclick="buy()">Buy</button>
</div>

<script>
function deposit() {
  alert("Deposit function coming soon");
}

function withdraw() {
  alert("Withdraw function coming soon");
}

function buy() {
  alert("Plan purchased (Demo only)");
}
</script>

</body>
</html>
