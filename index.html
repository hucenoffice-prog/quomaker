<!DOCTYPE html>
<html>
<head>
<meta charset='utf-8'>
<title>Quotation Maker</title>
<style>
body{font-family:Arial;margin:20px;background:#f4f4f4}
.container{max-width:1000px;margin:auto;background:#fff;padding:20px;border-radius:8px}
table{width:100%;border-collapse:collapse}
th,td{border:1px solid #ccc;padding:8px}
input{width:100%;padding:5px;box-sizing:border-box}
button{padding:10px 15px;margin:5px}
.total{font-size:20px;font-weight:bold;text-align:right}
@media print {.noprint{display:none}}
</style>
</head>
<body>
<div class='container'>
<h2>Quotation Maker</h2>
<label>Company Name</label><input id='company'>
<label>Customer Name</label><input id='customer'>
<label>Date</label><input type='date' id='date'>
<br><br>
<table id='items'>
<tr><th>Description</th><th>Qty</th><th>Unit Price</th><th>Total</th></tr>
<tr>
<td><input></td>
<td><input type='number' value='1' class='qty'></td>
<td><input type='number' value='0' class='price'></td>
<td class='lineTotal'>0.00</td>
</tr>
</table>
<div class='noprint'>
<button onclick='addRow()'>Add Item</button>
<button onclick='window.print()'>Print / Save PDF</button>
</div>
<p class='total'>Grand Total: <span id='grand'>0.00</span></p>
</div>
<script>
function calc(){
let grand=0;
document.querySelectorAll('#items tr').forEach((r,i)=>{
if(i===0)return;
let q=r.querySelector('.qty').value||0;
let p=r.querySelector('.price').value||0;
let t=q*p;
r.querySelector('.lineTotal').innerText=t.toFixed(2);
grand+=t;
});
document.getElementById('grand').innerText=grand.toFixed(2);
}
function addRow(){
let tr=document.createElement('tr');
tr.innerHTML=`<td><input></td><td><input type='number' value='1' class='qty'></td><td><input type='number' value='0' class='price'></td><td class='lineTotal'>0.00</td>`;
document.getElementById('items').appendChild(tr);
tr.querySelectorAll('input').forEach(i=>i.addEventListener('input',calc));
}
document.addEventListener('input',calc);
calc();
</script>
</body>
</html>
