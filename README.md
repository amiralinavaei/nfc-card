<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>اطلاعات تماس</title>
</head>
<body>

<h2>اطلاعات تماس</h2>

<p>شماره کارت:</p>
<p id="card">6104339912345678</p>

<button onclick="copyCard()">کپی شماره کارت</button>

<p id="result"></p>

<p><a href="tel:09123456789">📞 تماس</a></p>

<p><a href="https://wa.me/989123456789">💬 واتساپ</a></p>

<p><a href="https://instagram.com/USERNAME">📷 اینستاگرام</a></p>

<script>
function copyCard() {
var number = document.getElementById("card").innerText;
navigator.clipboard.writeText(number);
document.getElementById("result").innerText = "شماره کارت کپی شد ✓";
}
</script>

</body>
</html>
