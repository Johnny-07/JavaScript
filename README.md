<!DOCTYPE html>
<html>
<title>CS110 Group Project</title>
<body>

<h1>Group 3 Project</h1>

<form>
<input type="text">
<input type="submit" value="Submit"><br>
unsigned binary:<output name="unsigned binary">
One's compliment:<output name="1s compliment">
Two's compliment:<output name="2s compliment">
<p id="Binary"></p>
</output>
</form>
<script type="text/javascript">
document.getElementById("Binary").innerHTML = dec2bin();
function dec2bin(dec){
    return (dec >>> 0).toString(2);
}
</script>
</body>
</html>
