# JavaScript-Luvut

<!DOCTYPE html>
<html lang=fi>
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Javascript luvut</title>
        <style>
            p{
                font-family: 'Courier New', Courier, monospace;
                color: blue;
            }

            h1{
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                color: blue;
            }

        </style>
	</head>
    <body style="background-image: url(tausta.gif);">
        
        <h1>Tehtävä 1. Ohjelma, joka laskee kolmen syötetyn luvun keskiarvon.</h1>

        <p><br><br>Anna kolme lukua, niin lasken niiden keskiarvon!</p>
        <p id="luvut">Annoit luvut x, y, z</p>
        <p id="sum">Antamiesi lukujen summa = </p>
        <p id="ka">Antamiesi lukujen keskiarvo = </p>

        <a href="JSluvut1(1).html"><br><br>Takaisin</a>


		<script>

                var x = 0;
                var y = 0;
                var z = 0;

                x = prompt("Anna ensimmäinen luku");
                y = prompt("Anna toinen luku");
                z = prompt("Anna kolmas luku");
                
             x = parseInt(x);
             y = parseInt(y);
             z = parseInt(z);

                var summa = x + y + z;
                var keskiarvo = (x + y + z)/3;

                document.getElementById("luvut").innerHTML = "Annoit luvut: " + " " + x + ", " + y + " ja " + z;
                document.getElementById("sum").innerHTML = "Antamiesi lukujen summa = " + summa;
                document.getElementById("ka").innerHTML = "Antamiesi lukujen keskiarvo = " + keskiarvo;
        </script>
	</body>


</html>
