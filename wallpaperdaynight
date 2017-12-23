/* Piccolo script in PHP che consente di cambiare lo sfondo di un sito in un determinato orario */
/* Created by RickNaples91 */

<?php

/* imposto le variabili principali */
$alba=6; 
$giorno=18;
$ora=date("H");

/* Se soddisfa la condizione, imposta uno sfondo per l'alba*/

if($ora >= 3 && $ora <= $alba)
{
echo"<style>";
echo"body";
echo"{";
echo"background-image:url(https://66.media.tumblr.com/34abc9b3b86d41562689ae45823a69f2/tumblr_nyjgrvFCK41u7gnm9o1_500.gif);";
echo"background-repeat:repeat, no-repeat;";
echo"background-attachment:fixed, fixed;";
echo"background -position:center;";
echo"}";
echo"</style>";
}

/* Se soddisfa la condizione, imposta uno sfondo per il giorno */

elseif($ora > $alba && $ora <= $giorno)
{
echo"<style>";
echo"body";
echo"{";
echo"background-image:url(https://i.imgur.com/ra3uhKl.jpg);";
echo"background-repeat:repeat, no-repeat;";
echo"background-attachment:fixed, fixed;";
echo"background -position:center;";
echo"}";
echo"</style>";
}
else
{ 

/* Sfondo della notte */
echo"<style>";
echo"body";
echo"{";
echo"background-image:url(https://i.imgur.com/XfIDpPc.jpg);";
echo"background-repeat:repeat, no-repeat;";
echo"background-attachment:fixed, fixed;";
echo"background -position:center;";
echo"}";
echo"</style>";
}
?>
