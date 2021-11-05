
<html>
<head>
	
	<meta charset="UTF-8">
	<style>
		body{background-color:#bbf9f0;}
		h1{color:#282CAB;}
		h1,h2,h3{font-style:italic;}
		table {
			background-color:#FFFFFF;
			border:#1f750a solid 4px;
			width:500px;
			text-align:center;
			border-collapse:collapse;
		}
		td{border:#b5e9a9 solid 2px;}
		th{
			border:#f32c2c solid 2px;
			background-color: #ffda86;
			height:50px;
		}
		td{height:30px;}
	</style>
</head>
<body>
<h1>Les tableaux</h1>
<h2>Tableau tout simple</h2>
<table>
<tr><td>a</td><td>b</td><td>c</td></tr>
<tr><td>d</td><td>e</td><td>f</td></tr>
</table>
<h3>Ajouter un titre à son tableau</h3>
<p>C'est la balise caption qui  s'ajoute après la balise table</p>
<table>
<caption>Meilleur titre du monde</caption>
<tr><td>a</td><td>b</td><td>c</td></tr>
<tr><td>d</td><td>e</td><td>f</td></tr>
</table>
<h3>Cellule de titre</h3>
<table>
<caption>Couleurs dans différentes langues </caption>
<tr><th>Français</th><th>Anglais</th><th>Allemand</th></tr>
<tr><td>rouge</td><td>red</td><td>rot</td></tr>
<tr><td>jaune</td><td>yellow</td><td>gelb</td></tr>
<tr><td>bleu</td><td>blue</td><td>blau</td></tr>
</table>
<h2>Fusion des cellules</h2>
<h3>Avec l'attribut colspan : fusion horizontale</h3>
<table>
<caption>la météo du jour</caption>
<tr><th colspan="2">Mercredi 8 septembre 2021</th></tr>
<tr><td width="250px"><p>Matin<br>Soleil<br>23°</p></td><td><p>Après-midi<br>Orageux<br>30°</p></td></tr>
</table>
<h3>Avec l'attribut rowspan : fusion verticale</h3>
<table>
<caption>entreprise</caption>
<tr><td rowspan="4">direction</th><td>Ventes</td></tr>
<tr><td>Marketing</td></tr>
<tr><td>Compta</td></tr>
<tr><td>RH</td></tr>
</table>
</body>
</html>