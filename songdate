<!-- created by RickNaples91 -->

<!doctype html>
<html>
<head>

<title>Riprodurre canzoni in una determinata data</title>
</head>

<!-- Script per riprodurre canzoni su dispositivi Apple e Android-->

<script type="text/javascript">

function init() {
var myAudio = document.getElementById("audio");
myAudio.addEventListener('ended', loopAudio, false);

}
function loopAudio() {
var myAudio = document.getElementById("audio");
myAudio.play();
}

</script>

<!-- Carica lo script per riprodurre le canzoni su dispositivi Apple e Android -->
<body onload="init();">

<?php

/* Impostazione variabili principali */
$canzone='24.12.2017';
$canzone2='25.12.2017';

/* Acquisisco in una variabile la data
$today = date("d.m.o");

/* Se soddisfa la condizione, in tale giorno produce una determinata canzone */

if ($canzone == $today)
{
echo"<audio id=\"audio\" src=\"canzone1.mp3\" controls autoplay>";

echo"</audio>";
}

else if ($canzone2== $today)
{

echo"<audio id=\"audio\" src=\"canzone2.mp3\" controls autoplay>";

echo"</audio>";

/* Se non soddisfa nessuna delle due condizioni, riproduce per il resto dei giorni questa canzone qui */
else
{

echo"<audio id=\"audio\" src=\"canzone.mp3\" controls=\"true\" autoplay=\"true\">";

echo"</audio>";
}

?>

</body>
</html>
