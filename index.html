<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Personal Expense Tracker - Kunal Kumar</title>
  <style>
    body { font-family: Arial, sans-serif; max-width: 500px; margin: 40px auto; padding: 20px; background: #f4f7f6; }
    .card { background: #fff; padding: 20px; border-radius: 8px; border: 1px solid #ddd; }
    input, select, button { width: 100%; padding: 10px; margin: 8px 0; box-sizing: border-box; }
    button { background: #1d4ed8; color: white; border: none; cursor: pointer; font-weight: bold; }
    ul { list-style: none; padding: 0; }
    li { display: flex; justify-content: space-between; padding: 8px; border-bottom: 1px solid #eee; }
  </style>
</head>
<body>
  <div class="card">
    <h2>Expense Tracker</h2>
    <h3>Total Balance: ₹<span id="balance">0</span></h3>
    <input type="text" id="desc" placeholder="Enter Description (e.g. Books, Travel)">
    <input type="number" id="amount" placeholder="Amount (+ for Income, - for Expense)">
    <button onclick="addTransaction()">Add Transaction</button>
    <ul id="list"></ul>
  </div>
  <script>
    let transactions = JSON.parse(localStorage.getItem('txns')) || [];
    function render() {
      const list = document.getElementById('list');
      list.innerHTML = '';
      let total = 0;
      transactions.forEach((t, i) => {
        total += t.amount;
        list.innerHTML += `<li><span>${t.desc}</span><span>₹${t.amount} <button style="width:auto;padding:2px 6px;background:red;" onclick="del(${i})">x</button></span></li>`;
      });
      document.getElementById('balance').innerText = total;
      localStorage.setItem('txns', JSON.stringify(transactions));
    }
    function addTransaction() {
      const desc = document.getElementById('desc').value;
      const amount = parseFloat(document.getElementById('amount').value);
      if (!desc || isNaN(amount)) return alert('Please enter valid details');
      transactions.push({ desc, amount });
      document.getElementById('desc').value = '';
      document.getElementById('amount').value = '';
      render();
    }
    function del(index) { transactions.splice(index, 1); render(); }
    render();
  </script>
</body>
</html>
