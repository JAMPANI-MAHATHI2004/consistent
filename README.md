# consistent
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="calculator.css">
</head>
<body style="background-color: rgb(16, 16, 16);">
    <br>
    <br>
    <br>
    <br>
    <div class="flexbox">
        <form name="form">
            <input id="calculator" class="bar" type="text" name="result" style="height: 40px; width: 180px;"><br><br>
            <input id="clean" class="blocks" type="button" value="AC" onclick="form.result.value = ' '" style="height: 45px; width: 45px; color: green;">
            <input class="equal" type="button" value="=" onclick="form.result.value = eval(form.result.value)" style="height: 45px; width: 141px; color: green;">
            <br><br>
            <input class="blocks" type="button" value="7" onclick="form.result.value += '7'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="8" onclick="form.result.value += '8'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="9" onclick="form.result.value += '9'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="*" onclick="form.result.value += '*'" style="height: 45px; width: 45px; color: green;">
            <br><br>
            <input class="blocks" type="button" value="4" onclick="form.result.value += '4'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="5" onclick="form.result.value += '5'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="6" onclick="form.result.value += '6'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="-" onclick="form.result.value += '-'" style="height: 45px; width: 45px; color: green;">
            <br><br>
            <input class="blocks" type="button" value="1" onclick="form.result.value += '1'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="2" onclick="form.result.value += '2'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="3" onclick="form.result.value += '3'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="+" onclick="form.result.value += '+'" style="height: 45px; width: 45px; color: green;">
            <br><br>
            <input class="blocks" type="button" value="." onclick="form.result.value += '.'" style="height: 45px; width: 45px; color: green;">
            <input class="blocks" type="button" value="0" onclick="form.result.value += '0'" style="height: 45px; width: 45px;">
            <input class="blocks" type="button" value="%" onclick="form.result.value += '%'" style="height: 45px; width: 45px; color: green;">
            <input class="blocks" type="button" value="/" onclick="form.result.value += '/'" style="height: 45px; width: 45px; color: green;">
        </form>
    </div>
</body>
</html>
