# celine
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jQuery Example</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
</head>
<body>

<button id="show-alert">點擊我顯示警告</button>

<script>
$(document).ready(function(){
    $("#show-alert").click(function(){
        alert("這是一個警告對話框！");
    });
});
</script>

</body>
</html>



