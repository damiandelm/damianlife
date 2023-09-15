<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Voorbeeld</title>
</head>
<body>

<h1>Mijn Eerste JavaScript Webpagina</h1>

<p id="demo">Dit is een voorbeeldtekst.</p>

<button type="button" onclick="veranderTekst()">Verander tekst</button>

<script>
// JavaScript-code om de tekst te wijzigen wanneer op de knop wordt geklikt
function veranderTekst() {
    document.getElementById("demo").innerHTML = "De tekst is gewijzigd!";
}
</script>

</body>
</html>
